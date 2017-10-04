-include ../tools.mk

all:
	$(RUSTC) -C extra-filename=bar foo.rs -C save-temps
	rm $(TMPDIR)/foobar.foo.cgu-0.o
	rm $(TMPDIR)/$(call BIN,foobar)
