include ../../../s2n.mk

BCS=$(wildcard *.bc)

all_llvm.bc : $(BCS)
	$(LLVMLINK) -o $@ $+

bike_llvm.bc : $(BCS)
	$(LLVMLINK) -o $@ $+
