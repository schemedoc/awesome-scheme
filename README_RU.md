# Awesome Scheme на русском

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Содержание

- [Мероприятия (2021)](#мероприятия-2021)
- [Пропаганда](#пропаганда)
- [Стандарты](#стандарты)
- [Реализации](#реализации)
- [Менеджеры пакетов](#менеджеры-пакетов)
- [Книги](#книги)
- [Исследовательские работы](#исследовательские-работы)
- [Редакторы и среды разработки](#редакторы-и-среды-разработки)
- [Приложения](#приложения)
- [Веб-разработка](#веб-разработка)
- [Обработка текста](#обработка-текста)
- [Графика, музыка, аудио, видео](#графика-музыка-аудио-видео)
- [Языки и вычисления](#языки-и-вычисления)
- [Прошедшие мероприятия](#прошедшие-мероприятия)

## Пропаганда

* [Why _Structure and Interpretation of Computer Programs_ matters](https://people.eecs.berkeley.edu/~bh/sicp.html)
* [Why Write Compilers in Scheme?](https://blog.theincredibleholk.org/blog/2013/07/09/why-write-compilers-in-scheme/)
* [Why LambdaChip is using Scheme](https://lambdachip.com/articles/news/11)

## Стандарты

* [R<sup>5</sup>RS](https://schemers.org/Documents/Standards/R5RS/r5rs.pdf) (1998, [ошибки](http://mumble.net/~kelsey/r5rs-errata.html))
* **R<sup>6</sup>RS** (2007; [неофициальная исправленная версия](https://weinholt.se/scheme/r6rs/r6rs.pdf); [ошибки](http://www.r6rs.org/r6rs-errata.html); [official version](http://www.r6rs.org/final/r6rs.pdf))
  * Библиотеки ([неофициальная исправленная версия](https://weinholt.se/scheme/r6rs/r6rs-lib.pdf); [официальная версия](http://www.r6rs.org/final/r6rs-lib.pdf))
  * Дополнения ([неофициальная исправленная версия](https://weinholt.se/scheme/r6rs/r6rs-app.pdf); [официальная версия](http://www.r6rs.org/final/r6rs-app.pdf))
  * Обоснование ([неофициальная исправленная версия](https://weinholt.se/scheme/r6rs/r6rs-rationale.pdf); [официальная версия](http://www.r6rs.org/final/r6rs-rationale.pdf))
* **R<sup>7</sup>RS** (2013; [исправленная версия](https://standards.scheme.org/unofficial/errata-corrected-r7rs.pdf); [опечатки](https://github.com/johnwcowan/r7rs-work/blob/master/R7RSSmallErrata.md); [оригинальная версия](https://standards.scheme.org/official/r7rs.pdf))
* [R<sup>7</sup>RS large edition](https://github.com/johnwcowan/r7rs-work/blob/master/R7RSHomePage.md) (в процессе написания)
* [SRFI (Scheme Requests for Implementation)](https://srfi.schemers.org/)

## Реализации

### Компиляторы в нативный код

* [Chez Scheme](https://cisco.github.io/ChezScheme/): R6RS, официальный установщик в том числе и для Windows, считается одной из самых быстрых реализаций Scheme.
* [Ikarus](http://ikarus-scheme.org/) R6RS
* [MIT/GNU Scheme](https://www.gnu.org/software/mit-scheme/): R7RS

### Основанные на другой Scheme

* [Gerbil](https://cons.io/): R7RS, компилируется в C, основана на Gambit, расширяет Gambit более совершенными системами макросов и модулей.
* [**Racket**](https://racket-lang.org/): R6RS, удобная для начинающих, полная поддержка Windows, необязательная
  типизация, по сути, надмножество Scheme, тонны библиотек, перешла на Chez Scheme в качестве бэкенда.

### Компиляторы в C

* [**CHICKEN**](https://www.call-cc.org/): R5RS и R7RS, дружелюбная к новичкам, исключительное сообщество, уникальная реализация сборщика мусора.
* [Cyclone](https://justinethier.github.io/cyclone/): R7RS, экспериментальное расширение сборщика мусора в стиле Chicken с поддержкой нативных потоков.
* [Gambit](http://dynamo.iro.umontreal.ca/wiki/index.php/Main_Page): R5RS, официальные инсталляторы есть также для
  macOS, iOS, Windows, считается довольно быстрой.
* [Bigloo](https://www-sop.inria.fr/mimosa/fp/Bigloo/): R5RS, может компилироваться в Java-Virtual-Machine (JVM) классы, с
  ограниченной необязательной типизацией.

### Виртуальные машины и JVM/CLR

* [Chibi-Scheme](http://synthcode.com/wiki/chibi-scheme): R7RS
* [Gauche](https://practical-scheme.net/gauche/): R7RS, компилируется в автономный
  исполняемый файл, официальные инсталляторы есть также для Windows, есть Docker образ.
* [**GNU Guile**](https://www.gnu.org/software/guile/): R6RS, есть JIT компилятор, дружелюбная к новичкам, официально поддерживается GNU, язык сценариев для многих частей программного обеспечения GNU.
* [IronScheme](https://github.com/leppie/IronScheme): R6RS, работает на Common-Language-Runtime (CLR).
* [Kawa](https://www.gnu.org/software/kawa/): R7RS, работает на JVM, компилируется в JVM классы, ограниченная необязательная типизация.
* [STklos](http://stklos.net): R7RS за исключением системы модулей; ad-hoc переносимая ВМ, с CLOS-подобной системой объектов.

### Основанные на JavaScript

* [BiwaScheme](https://www.biwascheme.org/): R6RS, частично R7RS, компилятор в промежуточное представление + ВМ.
* [LIPS](https://lips.js.org/): R7RS, большая часть спецификации написана на ядре Scheme, хорошее взаимодействие с JavaScript.

### Реализованные на Python

* [Calysto Scheme](https://github.com/Calysto/calysto_scheme): частично R6RS, написана на Scheme, транслирована в Python.

## Менеджеры пакетов

* [Akku](https://akkuscm.org/): для переносимых R6RS и R7RS библиотек.
* [Snow](http://snow-fort.org/): для переносимых R7RS библиотек.
* [GNU Guix](https://www.gnu.org/software/guix/): чисто функциональный менеджер пакетов и дистрибутив GNU/Linux.
* [Racket Packages](https://pkgs.racket-lang.org/): для библиотек и приложений Racket.

## Книги

* [**Структура и интерпретация компьютерных программ**](https://www.ozon.ru/product/struktura-i-interpretatsiya-kompyuternyh-programm-5322055/): классический учебник по информатике от Массачусетского технологического института.
* [How to Design Programs](https://htdp.org/): более простой в обращении, более приземленный аналог СИКП.
* [The Little Schemer](https://ia800108.us.archive.org/4/items/Schemer/The%20Little%20Schemer.pdf): учит рекурсивному мышлению с помощью Scheme ([код](https://github.com/pkrumins/the-little-schemer)).
* [The Seasoned Schemer](https://mitpress.mit.edu/books/seasoned-schemer-second-edition): продолжение The Little Schemer ([код](https://github.com/pkrumins/the-seasoned-schemer)).
* [The Reasoned Schemer](https://mitpress.mit.edu/books/reasoned-schemer-second-edition): учит логическому программированию с использованием Scheme ([код](https://github.com/pkrumins/the-reasoned-schemer)).
* [The Scheme Programming Language](https://www.scheme.com/tspl4/): справочник по языку от автора Chez Scheme.
* [Essentials of Programming Languages](http://eopl3.com/): книга про реализацию языков программирования.

## Исследовательские работы

* [Bibliography of Scheme research](https://github.com/schemedoc/bibliography)

## Редакторы и среды разработки

* [Geiser](https://www.nongnu.org/geiser/): Emacs пакет для наиболее полной поддержки разных реализаций Scheme. ([MELPA](https://melpa.org/#/geiser))
* [Scheme-langserver](https://github.com/ufo5260987423/scheme-langserver): новый LSP сервер для Scheme, ориентированный на обработку неполного исходного кода и предоставление полезных возможностей языка. Он отличается от других REPL тем, что обеспечивает автодополнение локальных идентификаторов и многие другие возможности.

## Приложения

* [GNUCash](https://www.gnucash.org/): приложение для личных финансов, которое можно программировать с помощью Guile
* [SIAG: Scheme In A Grid](http://siag.nu/siag/): старый табличный редактор который можно программировать на Scheme, со встроенным веб-сервером.

## Веб-разработка

* [**SXML**](http://okmij.org/ftp/Scheme/SXML.html): очень популярное представление XML/HTML в виде S-выражений.
* [CSS-expressions](https://docs.racket-lang.org/css-expr/): представление CSS в виде S-выражений (Racket).
* chibi html-parser: мягкий парсер HTML (R7RS; [Документация](http://snow-fort.org/s/gmail.com/alexshinn/chibi/html-parser/0.5.7/index.html); Akku, Snow).

## Обработка текста

* [**Scribble**](https://docs.racket-lang.org/scribble/): популярный, относительно легковесный язык разметки на основе Scheme (Racket, [R7RS](http://snow-fort.org/pkg)).
* [Skribilo](https://www.nongnu.org/skribilo/): TeX/LaTeX-подобный процессор документов который можно программировать на Scheme.
* [Skribe](http://www-sop.inria.fr/mimosa/fp/Skribe/) и [Scheme Scribe](http://www-sop.inria.fr/members/Manuel.Serrano/scribe/): более старые процессоры документов на основе Scheme от INRIA.
* [Pollen](https://docs.racket-lang.org/pollen/): необычная система набора текста для написания целых книг на Racket.

## Графика, музыка, аудио, видео

* [LilyPond](https://lilypond.org/): программа нотной записи которую можно программировать на Scheme.
* [libfive](https://libfive.com/studio/): управляемая сценариями САПР твердотельного моделирования на основе Guile.
* [Fluxus](https://www.pawfal.org/fluxus/): переносимый игровой 3D движок для "живого" кодирования на Scheme.
* [Impromptu](http://impromptu.moso.com.au): "живое" кодирование с помощью Scheme на macOS.
* [Extempore](https://extemporelang.github.io): переносимое "живое" кодирование в Scheme.
* [Scheme For Max](https://github.com/iainctduncan/scheme-for-max): "живое" кодирование на Scheme в Max/MSP.

## Языки и вычисления

* [Nanopass Framework](https://nanopass.org/): предметно-ориентированный язык для разделения компиляторов на множество мелких проходов и промежуточных представлений.
* [Harlan](https://github.com/eholk/harlan): язык программирования на основе Scheme для вычислений на GPU.
* [packrat](http://tech.labs.oliverwyman.com/downloads/dev.lshift.net/tonyg/packrat.pdf): генератор синтаксического анализатора по РВ-грамматике с предметно-ориентированным языком на Scheme ([Akku](https://akkuscm.org/packages/packrat/), [Chicken](http://wiki.call-cc.org/eggref/5/packrat), [Racket](https://pkgs.racket-lang.org/package/Packrat)).
* r6rs-pffi - переносимый интерфейс внешних функций для нескольких реализаций Scheme (R6RS; [Страница и документация](https://github.com/ktakashi/r6rs-pffi); Akku).

## Прошедшие мероприятия

### 2022

* [Практикум по Scheme и функциональному программированию на ICFP](https://icfp22.sigplan.org/home/scheme-2022): 16 сентября - Любляна, Словения

### 2021

* [Практикум по Scheme и функциональному программированию на ICFP](https://icfp21.sigplan.org/home/scheme-2021): 27 августа - виртуальное
* [Европейский симпозиум по Лиспу](https://european-lisp-symposium.org/2021/): 3-4 мая - виртуальное

### 2020

* [Racketfest](https://racketfest.com): 27 февраля - Берлин, Германия
* [Европейский симпозиум по Лиспу](https://european-lisp-symposium.org/2020/): 27-28 апреля - виртуальное
* [Практикум по Scheme и функциональному программированию на ICFP](https://icfp20.sigplan.org/home/scheme-2020): 24-26 августа - виртуальное
* [Симпозиум по динамическим языкам в SPLASH](https://conf.researchr.org/home/dls-2020): 15-20 ноября - Чикаго, США

### 2019

* [Практикум по Scheme и функциональному программированию на ICFP](https://thomas.gilray.org/scheme-2019/): 18 августа - Берлин, Германия
* [Практикум, посвященный 30-летию Gambit Scheme](https://github.com/gambit/gambit-at-30): 12-13 октября - Монреаль, Канада
