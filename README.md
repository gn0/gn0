
## Repositories

### Data analysis

- [`tomltable`](https://github.com/gn0/tomltable): A command-line utility for generating LaTeX tables. The table specification is read from a TOML file. The table content is loaded from JSON files. Written in Python.
- [`jsonwriter`](https://github.com/gn0/jsonwriter): An R package that saves `fixest` estimation results in JSON files.
- [`json_this`](https://github.com/gn0/json-this): A Stata package that provides wrappers around `reg`, `reghdfe`, `ttest`, and arbitrary r-class and e-class Stata commands to save their results in JSON files.
- [`coeftable`](https://github.com/gn0/coeftable) and [`extract_from_stata`](https://github.com/gn0/extract-from-stata): Obsolete. Command-line utilities for generating regression tables from JSON files and Stata log files.

### Utilities

- [`tzconv`](https://github.com/gn0/tzconv): A command-line utility that converts a date and time from one time zone to several others. Written in Python.
- [`sacsv`](https://github.com/gn0/sacsv): "Swiss Army CSV." A variety of command-line utilities for manipulating CSV files. Written in Python.
- [`csvgears`](https://github.com/gn0/csvgears): Command-line utilities for high-performance manipulation of CSV files. Written in Rust.
- [`bibdl`](https://github.com/gn0/bibdl): A command-line utility that downloads BibTeX citation data based on a journal link for a paper. Written in Racket.
- [`lsx86features`](https://github.com/gn0/lsx86features): A command-line utility to list x86 instruction set extensions that are used by a compiled binary. Useful for verifying whether your Rust, C, or C++ compiler uses less frequently available instructions, e.g., AVX-512 vector instructions, when your computer supports them. Written in Perl.

### Survey tooling

- [Kidadisi](https://github.com/gn0/kidadisi): An R package to build survey definitions and use them to generate [XLSForm](https://xlsform.org/en/) questionnaires for [SurveyCTO](https://www.surveycto.com/) and [KoboToolbox](https://www.kobotoolbox.org/). Its goal is to make it easier to specify and edit surveys and track them in version control. Unlike Honeybee below which uses its own domain-specific language, Kidadisi aims to work with tooling such as RStudio which research teams may already be familiar with.
- [Honeybee](https://github.com/gn0/honeybee): Obsolete. A transpiler prototype to convert plain-text, human-readable survey definitions into XLSForm questionnaires for SurveyCTO. Designed to make survey editing easier, safer, and transparent to track in version control.
