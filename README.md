# A repository of MetaOCaml packages

A repository of [OPAM][opam] packages for [OCaml extended with modular implicits][ocaml-modular-implicits].

| ![implicits Ubuntu status](https://github.com/modular-implicits/modular-implicits-opam/workflows/Ubuntu-implicits/badge.svg) | ![implicits macOS status](https://github.com/modular-implicits/modular-implicits-opam/workflows/macOS-implicits/badge.svg) |
|---|---|
| ![implicits+BER Ubuntu status](https://github.com/modular-implicits/modular-implicits-opam/workflows/Ubuntu-implicits-ber/badge.svg) | ![implicits+BER macOS status](https://github.com/modular-implicits/modular-implicits-opam/workflows/macOS-implicits-ber/badge.svg) |

### Setting up

```
opam update
opam switch create 4.02.1+modular-implicits
opam remote add implicits git+https://github.com/modular-implicits/modular-implicits-opam.git
```

[ocaml-modular-implicits]: https://github.com/ocamllabs/ocaml-modular-implicits
[opam]: https://opam.ocaml.org/


### Current packages:

* [imp](https://github.com/modular-implicits/imp),
  experimental library using modular implicits
* [metaocaml-syb](https://github.com/yallop/staged-generic-programming),
  Staged version of the Scrap Your Boilerplate library
