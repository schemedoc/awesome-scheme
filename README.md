# Awesome Scheme

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Translations

* [Русский](README_RU.md)
* [Español](README_ES.md)

## Contents

- [Events (2021)](#events-2021)
- [Advocacy](#advocacy)
- [Standards](#standards)
- [Implementations](#implementations)
- [Package Managers](#package-managers)
- [Books](#books)
- [Research Papers](#research-papers)
- [Editors and IDEs](#editors-and-ides)
- [Applications](#applications)
- [Web Development](#web-development)
- [Text processing](#text-processing)
- [Graphics, Music, Audio, Video](#graphics-music-audio-video)
- [Languages and Computation](#languages-and-computation)
- [Past Events](#past-events)

## Advocacy

* [Why _Structure and Interpretation of Computer Programs_ matters](https://people.eecs.berkeley.edu/~bh/sicp.html)
* [Why Write Compilers in Scheme?](https://blog.theincredibleholk.org/blog/2013/07/09/why-write-compilers-in-scheme/)
* [Why LambdaChip is using Scheme](https://lambdachip.com/articles/news/11)

## Standards

* [R<sup>5</sup>RS](https://schemers.org/Documents/Standards/R5RS/r5rs.pdf) (1998, [errata](http://mumble.net/~kelsey/r5rs-errata.html))
* **R<sup>6</sup>RS** (2007; [unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs.pdf); [errata](http://www.r6rs.org/r6rs-errata.html); [official version](http://www.r6rs.org/final/r6rs.pdf))
  * Libraries ([unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs-lib.pdf); [official version](http://www.r6rs.org/final/r6rs-lib.pdf))
  * Appendices ([unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs-app.pdf); [official version](http://www.r6rs.org/final/r6rs-app.pdf))
  * Rationale ([unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs-rationale.pdf); [official version](http://www.r6rs.org/final/r6rs-rationale.pdf))
* **R<sup>7</sup>RS** (2013; [errata-corrected version](https://standards.scheme.org/unofficial/errata-corrected-r7rs.pdf); [errata](https://github.com/johnwcowan/r7rs-work/blob/master/R7RSSmallErrata.md); [original version](https://standards.scheme.org/official/r7rs.pdf))
* [R<sup>7</sup>RS large edition](https://github.com/johnwcowan/r7rs-work/blob/master/R7RSHomePage.md) (in progress)
* [SRFI (Scheme Requests for Implementation)](https://srfi.schemers.org/)

## Implementations

### Compiling to Native Code

* [Chez Scheme](https://cisco.github.io/ChezScheme/): R6RS, official installer also for Windows, considered one of the fastest scheme implementations.
* [Ikarus](http://ikarus-scheme.org/) R6RS
* [MIT/GNU Scheme](https://www.gnu.org/software/mit-scheme/): R7RS

### Based on Another Scheme

* [Gerbil](https://cons.io/): R7RS, compiles to C, based on Gambit,  extends gambit with better macro and module systems.
* [**Racket**](https://racket-lang.org/): R6RS, beginner friendly, full Windows support, optional
  typing, essentially a superset of scheme,  tons of libraries,  moving/moved to a Chez Scheme backend.

### Compiling to C

* [**CHICKEN**](https://www.call-cc.org/): R5RS and R7RS, beginner friendly, exceptional community, unique implementation of GC.
* [Cyclone](https://justinethier.github.io/cyclone/): R7RS,  experimental extension of Chicken-style GC with native thread support.
* [Gambit](http://dynamo.iro.umontreal.ca/wiki/index.php/Main_Page): R5RS, official installers also for
  macOS, iOS, Windows, considered quite fast.
* [Bigloo](https://www-sop.inria.fr/mimosa/fp/Bigloo/): R5RS, can also compile to Java-Virtual-Machine (JVM) classes,
  limited optional typing.

### Bytecode VMs and JVM/CLR

* [Chibi-Scheme](http://synthcode.com/wiki/chibi-scheme): R7RS
* [Gauche](https://practical-scheme.net/gauche/): R7RS, compiles to standalone
  executable, official installers also for Windows, Docker.
* [**GNU Guile**](https://www.gnu.org/software/guile/): R6RS, getting JIT executable support soon, beginner friendly, officially supported by GNU,  scripting language for many pieces of GNU software.
* [IronScheme](https://github.com/leppie/IronScheme): R6RS, based on Common-Language-Runtime (CLR).
* [Kawa](https://www.gnu.org/software/kawa/): R7RS, based on JVM, compile to JVM classes, limited optional typing.
* [STklos](http://stklos.net): R7RS except for the module system; ad-hoc portable VM, with CLOS-like object system.

### Based on JavaScript

* [BiwaScheme](https://www.biwascheme.org/): R6RS, partial R7RS, compiler to intermediate represantion + VM
* [LIPS](https://lips.js.org/): R7RS, most of the spec is written in core Scheme, good interop with JavaScript

### Implemented in Python

* [Calysto Scheme](https://github.com/Calysto/calysto_scheme): Partial R6RS, written in Scheme, transpiled to Python.

## Package Managers

* [Akku](https://akkuscm.org/): for portable R6RS and R7RS libraries
* [Snow](http://snow-fort.org/): for portable R7RS libraries
* [GNU Guix](https://www.gnu.org/software/guix/): purely-functional package manager and GNU/Linux distro
* [Racket Packages](https://pkgs.racket-lang.org/): for Racket libraries and applications

## Books

* [**Structure and Interpretation of Computer Programs**](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html): classic computer science textbook from MIT
* [How to Design Programs](https://htdp.org/): an easier-to-approach, more down-to-earth counterpart to SICP
* [The Little Schemer](https://ia800108.us.archive.org/4/items/Schemer/The%20Little%20Schemer.pdf): teaches recursive thinking using Scheme ([code](https://github.com/pkrumins/the-little-schemer))
* [The Seasoned Schemer](https://mitpress.mit.edu/books/seasoned-schemer-second-edition): continuation of The Little Schemer ([code](https://github.com/pkrumins/the-seasoned-schemer))
* [The Reasoned Schemer](https://mitpress.mit.edu/books/reasoned-schemer-second-edition): teaches logic programming using Scheme ([code](https://github.com/pkrumins/the-reasoned-schemer))
* [The Scheme Programming Language](https://www.scheme.com/tspl4/): language reference by the author of Chez Scheme
* [Essentials of Programming Languages](http://eopl3.com/): textbook on programming language implementation

## Research Papers

* [Bibliography of Scheme research](https://github.com/schemedoc/bibliography)

## Editors and IDEs

* [Geiser](https://www.nongnu.org/geiser/): most comprehensive Emacs support for many Scheme implementations ([MELPA](https://melpa.org/#/geiser))
* [Scheme-langserver](https://github.com/ufo5260987423/scheme-langserver): a new scheme language server focusing on digesting incomplete scheme source code and giving out useful language features. It's different from other REPL counterparts for it provides local identifier auto complete and many other functionalities.

## Applications

* [GNUCash](https://www.gnucash.org/): personal finance app scriptable in Guile
* [SIAG: Scheme In A Grid](http://siag.nu/siag/): old Scheme-scriptable spreadsheet with built-in web server

## Web Development

* [**SXML**](http://okmij.org/ftp/Scheme/SXML.html): very popular S-expression representation of XML/HTML
* [CSS-expressions](https://docs.racket-lang.org/css-expr/): S-expression representation of CSS (Racket)
* chibi html-parser: lenient HTML parser (R7RS; [Docs](http://snow-fort.org/s/gmail.com/alexshinn/chibi/html-parser/0.5.7/index.html); Akku, Snow)

## Text Processing

* [**Scribble**](https://docs.racket-lang.org/scribble/): popular, somewhat lightweight Scheme-based markup language (Racket, [R7RS](http://snow-fort.org/pkg))
* [Skribilo](https://www.nongnu.org/skribilo/): TeX/LaTeX-like document processor with Scheme scripting
* [Skribe](http://www-sop.inria.fr/mimosa/fp/Skribe/) and [Scheme Scribe](http://www-sop.inria.fr/members/Manuel.Serrano/scribe/): older Scheme-based document processors from INRIA
* [Pollen](https://docs.racket-lang.org/pollen/): a fancy typesetting system for writing entire books in Racket

## Graphics, Music, Audio, Video

* [LilyPond](https://lilypond.org/): music notation language with Scheme scripting
* [libfive](https://libfive.com/studio/): script-driven solid modeling CAD based on Guile
* [Fluxus](https://www.pawfal.org/fluxus/): portable 3D game engine for live coding in Scheme
* [Impromptu](http://impromptu.moso.com.au): live coding with Scheme on macOS
* [Extempore](https://extemporelang.github.io): portable live coding in Scheme
* [Scheme For Max](https://github.com/iainctduncan/scheme-for-max): live coding with Scheme in Max/MSP

## Languages and Computation

* [Nanopass Framework](https://nanopass.org/): a DSL for factoring compilers into many small passes and IRs
* [Harlan](https://github.com/eholk/harlan): a Scheme-based programming language for GPU computing
* [packrat](http://tech.labs.oliverwyman.com/downloads/dev.lshift.net/tonyg/packrat.pdf): a PEG parser generator with a Scheme DSL ([Akku](https://akkuscm.org/packages/packrat/), [Chicken](http://wiki.call-cc.org/eggref/5/packrat), [Racket](https://pkgs.racket-lang.org/package/Packrat))
* r6rs-pffi - portable foreign-function interface for several implementations (R6RS; [Home & Docs](https://github.com/ktakashi/r6rs-pffi); Akku)

## Past Events

## 2022

* [Scheme and Functional Programming Workshop at ICFP](https://icfp22.sigplan.org/home/scheme-2022): September 16 - Ljubljana, Slovenia

## 2021

* [Scheme and Functional Programming Workshop at ICFP](https://icfp21.sigplan.org/home/scheme-2021): August 27 - virtual
* [European Lisp Symposium](https://european-lisp-symposium.org/2021/): May 3-4 - virtual

### 2020

* [Racketfest](https://racketfest.com): February 27 - Berlin, Germany
* [European Lisp Symposium](https://european-lisp-symposium.org/2020/): April 27-28 - virtual
* [Scheme and Functional Programming Workshop at ICFP](https://icfp20.sigplan.org/home/scheme-2020): August 24-26 - virtual
* [Dynamic Languages Symposium at SPLASH](https://conf.researchr.org/home/dls-2020): November 15-20 - Chicago, USA

### 2019

* [Scheme and Functional Programming Workshop at ICFP](https://thomas.gilray.org/scheme-2019/): August 18 - Berlin, Germany
* [Gambit Scheme 30th anniversary workshop](https://github.com/gambit/gambit-at-30): October 12-13 - Montreal, Canada
