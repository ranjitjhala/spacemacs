# Ocaml contribution layer for Spacemacs

![logo](img/ocaml.png)

;; Generate TOC here, use the command `markdown-toc/generate-toc`

## Description

This is a very basic layer for editing ocaml files.

- Syntax highlighting via `tuareg-mode`
- Error reporting, completion and type display via `merlin`

## Install

To use this contribution add it to your `~/.spacemacs`

```elisp
(setq-default dotspacemacs-configuration-layers '(ocaml)
"List of contribution to load."
)
```

## OPAM packages

This layer requires some [opam](http://opam.ocaml.org) packages:

- `merlin`

To install them, use the following command: 

```sh
opam install merlin 
```

## TODO

- Add support for `flycheck` (using `flycheck-ocaml`)
- Add proper spacemacs key-bindings for basic merlin tasks
