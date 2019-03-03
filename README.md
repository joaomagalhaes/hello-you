# Hello 'You'

todo: add description

## Awk

  - [wiki](https://en.wikipedia.org/wiki/AWK): A special-purpose programming language designed for text processing and typically used as a data extraction and reporting tool.
  - first appeared: 1977
  - tiobe: 46
  - https://github.com/onetrueawk/awk

```sh
$ awk -f hi.awk <your_name>
```

## Bash

  - wiki: A Unix shell and command language.
  - first appeared: 1989
  - tiobe index as of march 2019: 41
  - check it out: https://www.gnu.org/software/bash/

```sh
$ sh hi.sh <your_name>
```

## C

  - wiki: A general-purpose, imperative computer programming language, supporting structured programming, lexical variable scope and recursion, while a static type system prevents many unintended operations.
  - first appeared: 1972
  - tiobe index as of march 2019: 2

```sh
$ gcc -o hi hi.c && ./hi <your_name>
```

## C++

  - wiki: A general-purpose programming language. It has imperative, object-oriented and generic programming features, while also providing facilities for low-level memory manipulation.
  - first appeared: 1985
  - tiobe index as of march 2019: 4
  - check it out: https://isocpp.org

```sh
$ g++ hi.cpp -o hi && ./hi <your_name>
```

## D

  - [wiki](https://en.wikipedia.org/wiki/D_(programming_language)): An object-oriented, imperative, multi-paradigm system programming language.
  - first appeared: 2001
  - tiobe index as of march 2019: 24
  - https://dlang.org

```sh
$ dmd hi.d && ./hi <your_name>
```

## Dart

  - wiki: An object-oriented, class defined, garbage-collected language using a C-style syntax. It supports interfaces, mixins, abstract classes, reified generics, static typing, and a sound type system.
  - first appeared: 2011
  - tiobe index as of march 2019: 23
  - check it out: https://www.dartlang.org

```sh
$ dart hi.dart <your_name>
```

## Go

  - wiki: A statically typed, compiled programming language. Syntactically similar to C, but with the added benefits of memory safety, garbage collection, structural typing, and CSP-style concurrency.
  - first appeared: 2009
  - tiobe index as of march 2019: 18
  - check it out: https://golang.org

```sh
$ go build hi.go && ./hi <your_name>
```

## Java

  - wiki: A general-purpose computer-programming language that is concurrent, class-based, object-oriented.
  - first appeared: 1995
  - tiobe index as of march 2019: 1

```sh
$ javac Hi.java && java Hi <your_name>
```

## JavaScript

  - wiki: A high-level, interpreted programming language characterized as dynamic, weakly typed, prototype-based and multi-paradigm.
  - first appeared: 1995
  - tiobe index as of march 2019: 7

```sh
$ node hi.js <your_name>
```

## Julia

  - wiki: A high-level general-purpose dynamic programming language whose designers intend it to address the needs of high-performance numerical analysis and computational science, without the need of separate compilation to be fast.
  - first appeared: 2012
  - tiobe index as of march 2019: 42
  - check it out: https://julialang.org

```sh
$ julia hi.jl <your_name>
```

## Kotlin

  - wiki: A cross-platform, statically typed, general-purpose programming language with type inference.
  - first appeared: 2011
  - tiobe index as of march 2019: 39
  - check it out: https://kotlinlang.org

```sh
$ kotlinc hi.kt -include-runtime -d hi.jar && java -jar hi.jar <your_name>
```

## Lua

  - wiki: A lightweight, multi-paradigm programming language designed primarily for embedded use in applications.
  - first appeared: 1993
  - tiobe index as of march 2019: 29
  - check it out: https://www.lua.org

```sh
$ lua hi.lua <your_name>
```

## Perl

  - wiki: A family of two high-level, general-purpose, interpreted, dynamic programming languages, Perl 5 and Perl 6.
  - first appeared: 1987
  - tiobe index as of march 2019: 13
  - check it out: https://www.perl.org

```sh
$ perl hi.pl <your_name>
```

## Python

  - wiki: An interpreted, high-level, general-purpose programming language.
  - first appeared: 1990
  - tiobe index as of march 2019: 3
  - check it out: https://www.python.org

```sh
$ python hi.py <your_name>
```

## Ring

  - [wiki](https://en.wikipedia.org/wiki/Ring_(programming_language)): A dynamically typed, general-purpose programming language. The supported programming paradigms are imperative, procedural, object-oriented, functional, meta, declarative using nested structures, and natural programming.
  - first appeared: 2016
  - tiobe: 50+
  - http://ring-lang.sourceforge.net

```sh
$ ring hi.ring <your_name>
```

## Ruby

  - wiki: A dynamic, interpreted, reflective, object-oriented, general-purpose programming language.
  - first appeared: 1995
  - tiobe index as of march 2019: 15
  - check it out: https://www.ruby-lang.org/en/

```sh
$ ruby hi.rb <your_name>
```

## Rust

  - wiki: A multi-paradigm systems programming language focused on safety, especially safe concurrency. Rust is syntactically similar to C++, but is designed to provide better memory safety while maintaining high performance.
  - first appeared: 2010
  - tiobe index as of march 2019: 35
  - check it out: https://www.rust-lang.org

```sh
$ rustc hi.rs && ./hi <your_name>
```
