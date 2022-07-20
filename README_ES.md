# Awesome Scheme en Español

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Traducciones

* [Русский](README_RU.md)
* [Inglés (original)](README.md)

## Contenido

- [Eventos (2021)](#eventos-2021)
- [Promoción](#promoción)
- [Estándares](#estándares)
- [Implementaciones](#implementaciones)
- [Gestores de paquetes](#gestores-de-paquetes)
- [Libros](#libros)
- [Trabajos de Investigación](#trabajos-de-investigación)
- [Editores e IDEs](#editores-e-ides)
- [Aplicaciones](#aplicaciones)
- [Desarrollo Web](#desarrollo-web)
- [Procesamiento de Texto](#procesamiento-de-texto)
- [Gráficos, Música, Audio, Vídeo](#gráficos-música-audio-vídeo)
- [Lenguajes y Computación](#lenguajes-y-computación)
- [Eventos Pasados](#eventos-pasados)

## Eventos (2021)

* [Taller de Scheme y Programación Funcional en la ICFP](https://icfp21.sigplan.org/home/scheme-2021): 27 de Agosto - virtual
* [Simposio Europeo de Lisp](https://european-lisp-symposium.org/2021/): 3-4 de Mayo - virtual

## Promoción

* [¿Por qué Escribir Compiladores en Scheme?](https://blog.theincredibleholk.org/blog/2013/07/09/why-write-compilers-in-scheme/)
* [¿Por qué LambdaChip usa Scheme?](https://lambdachip.com/articles/news/11)

## Estándares

* [R<sup>5</sup>RS](https://schemers.org/Documents/Standards/R5RS/r5rs.pdf) (1998, [errata](http://mumble.net/~kelsey/r5rs-errata.html))
* **R<sup>6</sup>RS** (2007; [versión no oficial corregida de erratas](https://weinholt.se/scheme/r6rs/r6rs.pdf); [errata](http://www.r6rs.org/r6rs-errata.html); [versión oficial](http://www.r6rs.org/final/r6rs.pdf))
  * Bibliotecas ([versión no oficial corregida de erratas](https://weinholt.se/scheme/r6rs/r6rs-lib.pdf); [versión oficial](http://www.r6rs.org/final/r6rs-lib.pdf))
  * Apéndices ([versión no oficial corregida de erratas](https://weinholt.se/scheme/r6rs/r6rs-app.pdf); [versión oficial](http://www.r6rs.org/final/r6rs-app.pdf))
  * Razón fundamental ([versión no oficial corregida de erratas](https://weinholt.se/scheme/r6rs/r6rs-rationale.pdf); [versión oficial](http://www.r6rs.org/final/r6rs-rationale.pdf))
* **R<sup>7</sup>RS** (2013; [versión corregida de erratas](https://standards.scheme.org/unofficial/errata-corrected-r7rs.pdf);
  [errata](https://github.com/johnwcowan/r7rs-work/blob/master/R7RSSmallErrata.md);
  [versión original](https://standards.scheme.org/official/r7rs.pdf))
* [R<sup>7</sup>RS edición grande](https://github.com/johnwcowan/r7rs-work/blob/master/R7RSHomePage.md) (en proceso)
* [SRFI (Solicitudes de Scheme para la implementación)](https://srfi.schemers.org/)

## Implementaciones

### Compiladores nativos

* [Chez Scheme](https://cisco.github.io/ChezScheme/): R6RS, instalador oficial también para Windows, considerada una de las más rápidas implementaciones de Scheme.
* [Ikarus](http://ikarus-scheme.org/) R6RS
* [MIT/GNU Scheme](https://www.gnu.org/software/mit-scheme/): R7RS

### Usan otro Scheme como backend

* [Gerbil](https://cons.io/): R7RS, compila a C, basado en Gambit,  extiende Gambit con mejores sistemas de macros y módulos.
* [**Racket**](https://racket-lang.org/): R6RS, amigable para principiantes, soporte completo para Windows, tipado opcional, esencialmente un superconjunto de Scheme, toneladas de bibliotecas, moviendo/movido a un backend de Chez Scheme.

### Transpiladores a C

* [**CHICKEN**](https://www.call-cc.org/): R5RS and R7RS, amigable para principiantes, comunidad excepcional, implementación única de GC.
* [Cyclone](https://justinethier.github.io/cyclone/): R7RS,  extensión experimental del GC estilo Chicken con soporte de hilos nativo.
* [Gambit](http://dynamo.iro.umontreal.ca/wiki/index.php/Main_Page): R5RS, instalador oficial también para macOS, iOS, Windows, considerado bastante rápido.
* [Bigloo](https://www-sop.inria.fr/mimosa/fp/Bigloo/): R5RS, también puede compilar a clases Java-Virtual-Machine (JVM), tipado opcional limitado.

### Bytecode de VM y JVM/CLR

* [Chibi-Scheme](http://synthcode.com/wiki/chibi-scheme): R7RS
* [Gauche](https://practical-scheme.net/gauche/): R7RS, compila a ejecutable independiente, instalador oficial también para Windows, Docker.
* [**GNU Guile**](https://www.gnu.org/software/guile/): R6RS, pronto soporte para ejecutable JIT, fácil de usar para principiantes, soportado oficialmente por GNU, lenguaje de scripting para muchas piezas de software GNU.
* [IronScheme](https://github.com/leppie/IronScheme): R6RS, basado en el Common-Language-Runtime (CLR).
* [Kawa](https://www.gnu.org/software/kawa/): R7RS, basado en la JVM, compila a clases JVM, tipado opcional limitado.
* [STklos](http://stklos.net): R7RS excepto por el sistema de módulos; VM portátil ad-hoc, con sistema de objetos similar a CLOS.

### Intérprete JavaScript

* [BiwaScheme](https://www.biwascheme.org/): R6RS, parcial R7RS, compilador a representación intermedia + VM.
* [LIPS](https://lips.js.org/): R7RS, la mayor parte de la especificación está escrita en core Scheme, buena interoperabilidad con JavaScript.

## Gestores de paquetes

* [Akku](https://akkuscm.org/): para bibliotecas portátiles R6RS y R7RS
* [Snow](http://snow-fort.org/): para bibliotecas portátiles R7RS
* [GNU Guix](https://www.gnu.org/software/guix/): administrador de paquetes puramente funcional y distribución GNU/Linux
* [Racket Packages](https://pkgs.racket-lang.org/): para bibliotecas y aplicaciones Racket

## Libros

* [**Structure and Interpretation of Computer Programs**](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html):
  libro de texto clásico de informática del MIT. [versión en español (incompleta/en proceso)](https://github.com/FedeHC/SICP-ES)
* [How to Design Programs](https://htdp.org/): una contraparte de SICP más fácil de abordar y con los pies en la tierra
* [The Little Schemer](https://ia800108.us.archive.org/4/items/Schemer/The%20Little%20Schemer.pdf): Enseña pensamiento recursivo usando Scheme ([code](https://github.com/pkrumins/the-little-schemer))
* [The Seasoned Schemer](https://mitpress.mit.edu/books/seasoned-schemer-second-edition): continuación de /The Little Schemer/ ([code](https://github.com/pkrumins/the-seasoned-schemer))
* [The Reasoned Schemer](https://mitpress.mit.edu/books/reasoned-schemer-second-edition): enseña programación lógica usando Scheme ([code](https://github.com/pkrumins/the-reasoned-schemer))
* [The Scheme Programming Language](https://www.scheme.com/tspl4/): Referencia del lenguaje por el autor de Chez Scheme
* [Essentials of Programming Languages](http://eopl3.com/): libro de texto sobre implementación de lenguajes de programación

## Trabajos de Investigación

* [Bibliografía de la investigación de Scheme](https://github.com/schemedoc/bibliography)

## Editores e IDEs

* [Geiser](https://www.nongnu.org/geiser/): el soporte de Emacs más completo para muchas implementaciones de Scheme ([MELPA](https://melpa.org/#/geiser))

## Aplicaciones

* [GNUCash](https://www.gnucash.org/): aplicación de finanzas personales programable en Guile
* [SIAG: Scheme In A Grid](http://siag.nu/siag/): antigua hoja de cálculo programable en Scheme con servidor web incorporado

## Desarrollo Web

* [**SXML**](http://okmij.org/ftp/Scheme/SXML.html): Representación de expresión-S muy popular de XML/HTML
* [CSS-expressions](https://docs.racket-lang.org/css-expr/): Representación de expresión-S de CSS (Racket)
* chibi html-parser: lenient HTML parser (R7RS; [Docs](http://snow-fort.org/s/gmail.com/alexshinn/chibi/html-parser/0.5.7/index.html); Akku, Snow)

## Procesamiento de Texto

* [**Scribble**](https://docs.racket-lang.org/scribble/): Lenguaje de marcado basado en Scheme, algo ligero y popular (Racket, [R7RS](http://snow-fort.org/pkg))
* [Skribilo](https://www.nongnu.org/skribilo/): Procesador de documentos similar a TeX/LaTeX con scripting en Scheme
* [Skribe](http://www-sop.inria.fr/mimosa/fp/Skribe/) y [Scheme Scribe](http://www-sop.inria.fr/members/Manuel.Serrano/scribe/): antiguos procesadores de documentos basados ​​en Scheme de INRIA
* [Pollen](https://docs.racket-lang.org/pollen/): un elegante sistema de composición tipográfica para escribir libros completos en Racket

## Gráficos, Música, Audio, Vídeo

* [LilyPond](https://lilypond.org/): lenguaje de notación musical con scripting en Scheme
* [libfive](https://libfive.com/studio/): CAD de modelado sólido orientado a scripting basado en Guile
* [Fluxus](https://www.pawfal.org/fluxus/): motor de juego 3D portátil para live coding en Scheme
* [Impromptu](http://impromptu.moso.com.au): live coding con Scheme en macOS
* [Extempore](https://extemporelang.github.io): live coding portable en Scheme
* [Scheme For Max](https://github.com/iainctduncan/scheme-for-max): live coding con Scheme en Max/MSP

## Lenguajes y Computación

* [Nanopass Framework](https://nanopass.org/): un DSL para factorizar compiladores en muchos pases pequeños e IRs
* [Harlan](https://github.com/eholk/harlan): un lenguaje de programación basado en Scheme para la computación por GPU
* [packrat](http://tech.labs.oliverwyman.com/downloads/dev.lshift.net/tonyg/packrat.pdf): un generador de analizado PEG con un Scheme DSL ([Akku](https://akkuscm.org/packages/packrat/), [Chicken](http://wiki.call-cc.org/eggref/5/packrat), [Racket](https://pkgs.racket-lang.org/package/Packrat))
* r6rs-pffi - interfaz portátil de funciones externas para varias implementaciones (R6RS; [Home & Docs](https://github.com/ktakashi/r6rs-pffi); Akku)

## Eventos pasados

### 2020

* [Racketfest](https://racketfest.com): 27 de Febrero - Berlin, Alemania
* [Simposio Europeo de Lisp](https://european-lisp-symposium.org/2020/): 27-28 de Abril - virtual
* [Taller de Scheme y Programación Funcional en la ICFP](https://icfp20.sigplan.org/home/scheme-2020): 24-26 de Agosto - virtual
* [Simposio de Lenguajes Dinámicos en SPLASH](https://conf.researchr.org/home/dls-2020): 15-20 de Noviembre - Chicago, Estados Unidos

### 2019

* [Taller de Scheme y Programación Funcional en la ICFP](https://thomas.gilray.org/scheme-2019/): 18 de Agosto - Berlin, Alemania
* [Taller del 30 aniversario de Gambit Scheme](https://github.com/gambit/gambit-at-30): 12-13 de Octubre - Montreal, Canadá
