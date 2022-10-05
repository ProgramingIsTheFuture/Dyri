# Dyri Language

Documentations for the packages used to build this language can be found at [dyri](https://programingisthefuture.github.io/Dyri/)

# Design

[design](https://programingisthefuture.github.io/Dyri/cli/design.html) can be found here!

# TODO

- [x] Deploy docs to github pages with github actions
- Update language design
  - [x] Better base type system
  - [x] Type definition
  - [x] More about the blocks
  - [ ] Import and Export (support multiple files in single project)
- Better AST
  - [x] Standard Ast
  - [x] Typed Ast
- [ ] Lexer to lex and parse all the new syntax into the AST
- [ ] Check the types that can be type-inferred and statically typed
- [ ] Compile to LLVM

# Plan

- Lex and Parse the language
- Check the types
- Compile to LLVM
- Support cross-compilation
- Import and Export libraries
- Start building externals libraries to general use of the language