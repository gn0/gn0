
## Repositories

### Data analysis

- [`tomltable`](https://github.com/gn0/tomltable): Generates LaTeX tables using table specifications in TOML. The table content is loaded from JSON files. Written in Python.
- [`jsonwriter`](https://github.com/gn0/jsonwriter): An R package that saves `fixest` estimation results in JSON files.
- [`json_this`](https://github.com/gn0/json-this): A Stata package that provides wrappers around `reg`, `reghdfe`, `ttest`, and arbitrary r-class and e-class Stata commands to save their results in JSON files.
- [`sacsv`](https://github.com/gn0/sacsv): "Swiss Army CSV." A variety of command-line utilities for manipulating CSV files. Written in Python.
- [`csvgears`](https://github.com/gn0/csvgears): Command-line utilities for high-performance manipulation of CSV files. Written in Rust.

### Utilities

- [`tzconv`](https://github.com/gn0/tzconv): Converts a date and time from one time zone to several others. Written in Python.
- [`lui`](https://github.com/gn0/lui): An LLM UI for the command line, using the API of open-webui. Written in Rust.
- [`bibdl`](https://github.com/gn0/bibdl): Downloads BibTeX citation data based on a journal link for a paper. Written in Racket.

### Various kinds of tooling

- [`lsx86features`](https://github.com/gn0/lsx86features): Lists x86 instruction set extensions that are used by a compiled binary. Useful for verifying whether your Rust, C, or C++ compiler uses less frequently available instructions, e.g., AVX-512 vector instructions, when your computer supports them. Written in Rust.
- [Steganotorchy](https://github.com/gn0/steganotorchy): Embeds an arbitrary secret message inside neural network weights and biases. Written in Rust. ([See blog post.](https://blog.gabornyeki.com/2024-11-hiding-a-message-in-my-pytorch-weights/))
- [dors](https://github.com/gn0/dors): A highly experimental re-implementation of OpenBSD's doas that aims at statically guaranteed correctness. Written in Rust.
- [nvim-web-server](https://github.com/gn0/nvim-web-server): Turns Neovim into a web server. Written in Lua. ([See blog post.](https://vim.gabornyeki.com/))
- [Sigh Mode](https://github.com/gn0/sigh-mode): Navigates an Emacs buffer sentence-by-sentence rather than character-by-character, and always highlights the current sentence. Written in Emacs Lisp.
- [vim-cheatsheet](https://github.com/gn0/vim-cheatsheet): Toggles a popup window with a buffer-specific cheatsheet. Written in Vim script.
- [vim-minimal-look](https://github.com/gn0/vim-minimal-look): Toggles whether status line, etc., are displayed. Written in Vim script.
- [Kidadisi](https://github.com/gn0/kidadisi): An R package to build survey definitions and use them to generate XLSForm questionnaires for SurveyCTO and KoboToolbox. Its goal is to make it easier to specify and edit surveys and track them in version control. Unlike Honeybee below which uses its own domain-specific language, Kidadisi aims to work with tooling such as RStudio which research teams may already be familiar with.
