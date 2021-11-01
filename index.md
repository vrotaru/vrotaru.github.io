# Hello

## LLVM Kaleidoscope Tutorial

The venerable [LLVM Kaleidoscope Tutorial](https://releases.llvm.org/8.0.0/docs/tutorial/OCamlLangImpl1.html) is a nice introduction to both [OCaml](https://ocaml.org) and [LLVM](https://llvm.org) but it implements parsing & lexing using the OCaml stream parsers, which are are no longer a feature of current OCaml versions. 

Of course, you don't need stream parser to parse stuff in OCamL, there is `ocamllex`, `ocamlyacc`/`menhir` for traditional lexer/parser approach.

There are many parser combinator libraries, just do a search on [OPAM](https://opam.ocaml.org/packages).

You can (probably) still use the `Camlp4` alternative/successor/predecessor [Camlp5](https://camlp5.github.io/)

Or you can read my attempt to do the same using just `ocamllex` and recursive descent parsing techniques. 

<https://vrotaru.github.io/llvm-kaleidoscope>
