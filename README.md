
## Repositories

### Data analysis

- [`tomltable`](https://github.com/gn0/tomltable): Generates LaTeX tables using table specifications in TOML. The table content is loaded from JSON files. Written in Python.
- [`jsonwriter`](https://github.com/gn0/jsonwriter): An R package that saves `fixest` estimation results in JSON files.
- [`json_this`](https://github.com/gn0/json-this): A Stata package that provides wrappers around `reg`, `reghdfe`, `ttest`, and arbitrary r-class and e-class Stata commands to save their results in JSON files.

### Utilities

- [`tzconv`](https://github.com/gn0/tzconv): Converts a date and time from one time zone to several others. Written in Python.
- [`sacsv`](https://github.com/gn0/sacsv): "Swiss Army CSV." A variety of command-line utilities for manipulating CSV files. Written in Python.
- [`csvgears`](https://github.com/gn0/csvgears): Command-line utilities for high-performance manipulation of CSV files. Written in Rust.
- [`bibdl`](https://github.com/gn0/bibdl): Downloads BibTeX citation data based on a journal link for a paper. Written in Racket.
- [`lsx86features`](https://github.com/gn0/lsx86features): Lists x86 instruction set extensions that are used by a compiled binary. Useful for verifying whether your Rust, C, or C++ compiler uses less frequently available instructions, e.g., AVX-512 vector instructions, when your computer supports them. Written in Rust.
- [Sigh Mode](https://github.com/gn0/sigh-mode): Navigate an Emacs buffer sentence-by-sentence rather than character-by-character, and always highlight the current sentence. Written in Emacs Lisp.

### Security tooling

- [Steganotorchy](https://github.com/gn0/steganotorchy): Embeds an arbitrary secret message inside neural network weights and biases. Written in Rust. ([See blog post.](https://blog.gabornyeki.com/2024-11-hiding-a-message-in-my-pytorch-weights/))
- [dors](https://github.com/gn0/dors): A re-implementation of [OpenBSD's doas](https://en.wikipedia.org/wiki/Doas) that aims at statically guaranteed correctness. Highly experimental. Written in Rust.

### Survey tooling

- [Kidadisi](https://github.com/gn0/kidadisi): An R package to build survey definitions and use them to generate [XLSForm](https://xlsform.org/en/) questionnaires for [SurveyCTO](https://www.surveycto.com/) and [KoboToolbox](https://www.kobotoolbox.org/). Its goal is to make it easier to specify and edit surveys and track them in version control. Unlike Honeybee below which uses its own domain-specific language, Kidadisi aims to work with tooling such as RStudio which research teams may already be familiar with.
