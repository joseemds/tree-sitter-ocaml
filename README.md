tree-sitter-reason
=================

ReasonML grammar for [tree-sitter](https://github.com/tree-sitter/tree-sitter).

This module a grammar for ReasonML files (`.re`) and interface (`.rei`) files.

ReasonML is an alternative syntax to OCaml, They both generate the same AST, but ReasonML has a syntax that is more close to javascript, so it parser is slightly diferent.


This is a fork from [tree-sitter-ocaml](https://github.com/tree-sitter/tree-sitter-ocaml) since they share a lot of similarities in the AST,  it changes the necessary to make ReasonML "parsable"

References

* [OCaml language reference](https://ocaml.org/manual/language.html)
* [OCaml language extensions](https://ocaml.org/manual/extn.html)
* [ReasonML parser](https://github.com/ocaml/ocaml/blob/trunk/parsing/parser.mly)
