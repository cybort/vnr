# Makefile
# 8/8/2013 jichi
include ../../qmljs.mk

all: Makefile compress

compress: $(wildcard *.min.js)

%.min.js: %.js
	$(MAKE) .closure OUT=$@ IN=$^

clean: .clean

# EOF
