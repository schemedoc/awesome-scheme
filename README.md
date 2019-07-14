# Awesome Scheme

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

- [Upcoming Events](#upcoming-events)
- [Standards](#standards)
- [Implementations](#implementations)
- [Package Managers](#package-managers)
- [Read, Learn, Teach](#read-learn-teach)
- [Editor and IDEs](#editor-and-ides)
- [Web Development](#web-development)
- [Past Events](#past-events)

## Upcoming Events

- [20th Annual Scheme and Functional Programming Workshop, 2019](https://thomas.gilray.org/scheme-2019/): Berlin, Germany

## Standards

* [R<sup>5</sup>RS](https://schemers.org/Documents/Standards/R5RS/r5rs.pdf) (1998, [errata](http://mumble.net/~kelsey/r5rs-errata.html))
* **R<sup>6</sup>RS** (2007; [unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs.pdf); [errata](http://www.r6rs.org/r6rs-errata.html); [official version](http://www.r6rs.org/final/r6rs.pdf))
  * Libraries ([unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs-lib.pdf); [official version](http://www.r6rs.org/final/r6rs-lib.pdf))
  * Appendices ([unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs-app.pdf); [official version](http://www.r6rs.org/final/r6rs-app.pdf))
  * Rationale ([unofficial errata-corrected version](https://weinholt.se/scheme/r6rs/r6rs-rationale.pdf); [official version](http://www.r6rs.org/final/r6rs-rationale.pdf))
* **R<sup>7</sup>RS** (2013; [errata-corrected version](https://bitbucket.org/cowan/r7rs/raw/errata/rnrs/r7rs.pdf); [errata](https://bitbucket.org/cowan/r7rs-wg1-infra/src/default/R7RSSmallErrata.md); [original version](https://bitbucket.org/cowan/r7rs/raw/errata/rnrs/r7rs-official.pdf))
* [R<sup>7</sup>RS large edition](https://bitbucket.org/cowan/r7rs-wg1-infra/src/default/R7RSHomePage.md) (in progress)
* [SRFI (Scheme Requests for Implementation)](https://srfi.schemers.org/)

## Implementations

### Native Compilers
* [Chez](https://cisco.github.io/ChezScheme/): R6RS, official installer also for Windows, considered one of the fastest scheme implementations.
* [Ikarus](http://ikarus-scheme.org/) R6RS
* [MIT/GNU Scheme](https://www.gnu.org/software/mit-scheme/): R7RS

### Uses another Scheme as backend
* [Gerbil](https://cons.io/): R7RS, compiles to C, based on Gambit,  extends gambit with better macro and module systems.
* [**Racket**](https://racket-lang.org/): R6RS, beginner friendly, full Windows support, optional
  typing, essentially a superset of scheme,  tons of libraries,  moving/moved to a Chez Scheme backend.

### Transpilers to C
* [**Chicken**](https://www.call-cc.org/): R5RS and R7RS, beginner friendly, exceptional community, unique implementation of GC.
* [Cyclone](https://justinethier.github.io/cyclone/): R7RS,  experimental extension of Chicken-style GC with native thread support.
* [Gambit](http://dynamo.iro.umontreal.ca/wiki/index.php/Main_Page): R5RS, official installers also for
  macOS, iOS, Windows, considered quite fast.
* [Bigloo](https://www-sop.inria.fr/mimosa/fp/Bigloo/): R5RS, can also compile to Java-Virtual-Machine (JVM) classes,
  limited optional typing.

### Bytecode VM's and JVM/CLR
* [Chibi](http://synthcode.com/wiki/chibi-scheme): R7RS
* [Gauche](https://practical-scheme.net/gauche/): R7RS, compiles to standalone
  executable, official installers also for Windows, Docker.
* [**GNU Guile**](https://www.gnu.org/software/guile/): R6RS, getting JIT executable support soon, beginner friendly, officially supported by GNU,  scripting language for many pieces of GNU software.
* [IronScheme](https://github.com/leppie/IronScheme): R6RS, based on Common-Language-Runtime (CLR).
* [Kawa](https://www.gnu.org/software/kawa/): R7RS, based on JVM, compile to JVM classes, limited optional typing.

### Javascript Interpreter
* [BiwaScheme](https://www.biwascheme.org/)

### Unmaintained
* [Larceny](http://larcenists.org/): R6RS and R7RS, generate native code, official installers also for macOS, Windows.
* [Scheme48](http://www.s48.org/): classic, unmaintained but useful.
* [Scsh](https://scsh.net/): classic, unmaintained but useful.
* [Ypsilon](http://www.littlewingpinball.com/doc/en/ypsilon/index.html): classic, unmaintained but useful.


## Package Managers

* [Akku](https://akkuscm.org/): Implementation agnostic R6RS and R7RS packages.
* [GNU Guix](https://www.gnu.org/software/guix/): Functional package manager and operating system distribution for GNU sytem.
* [Snow](http://snow-fort.org/): Portable R7RS libraries.
* [Racket](https://pkgs.racket-lang.org/): Racket-specific packages.

## Read, Learn, Teach

* [Bibliography of Scheme-related Research](https://github.com/scheme-live/bibliography#bibliography-of-scheme-related-research)
* [**Structure and Interpretation of Computer Programs**](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html): classic computer science textbook from MIT
* [The Scheme Programming Language 4th Edition](https://www.scheme.com/tspl4/): Written by Kent Dybvig of Chez Scheme fame.

## Editor and IDEs

* [Geiser](https://www.nongnu.org/geiser/): most comprehensive Emacs support for many Scheme implementations ([MELPA](https://melpa.org/#/geiser))

## Web Development

* _chibi html-parser_: lenient HTML parser (R7RS; [Docs](http://snow-fort.org/s/gmail.com/alexshinn/chibi/html-parser/0.5.7/index.html); Akku, Snow)

## Foreign Function Interface

* _r6rs-pffi_ - portable foreign-function interface for several implementations (R6RS; [Home & Docs](https://github.com/ktakashi/r6rs-pffi); Akku)

## Past Events
