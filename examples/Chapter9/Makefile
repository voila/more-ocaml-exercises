# Build the camlpdf library as byte code and native code
SOURCES = examples.ml

RESULT = examples

INCDIRS = ../../more/

LIBS = unix more 

OCAMLNCFLAGS = -g
OCAMLBCFLAGS = -g
OCAMLLDFLAGS = -g

all : native-code top

OCAMLMAKEFILE = ../../more/OCamlMakefile

include $(OCAMLMAKEFILE)
