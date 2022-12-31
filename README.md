# The Ocaml Plaform

## [Real World Ocaml](https://dev.realworldocaml.org/) documentation.

Make sure you first initialize opam’s global state.

```sh
$ opam init
```

See all the different sandboxed environments you have available.

```sh
$ opam switch
```

Creating a OCaml project and navigating around it.

```sh
$ dune init proj hello
```

- Dune has a basic built-in command to initialize a project template that is suitable to get us started.

Setting Up an Opam Local Switch

```sh
$ cd hello
$ opam switch create .
```

Get a full list of all the compilers that are available.

```sh
$ opam switch list-available
```

If you have OCaml 4.13.1 installed, then running this command will use the system compiler

```sh
$ opam switch create . 4.13.1
```

If you always want to locally install a particular compiler

```sh
$ opam switch create . ocaml-base-compiler.4.13.1
```
