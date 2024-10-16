---
title: 'Features'
description: ""
date: 2024-10-16T12:46:21+05:30
toc: true
tags: []
draft: false
---

## LLVM Features

The [LLVM compiler system](https://releases.llvm.org/) for C and C++ includes the following:

- Front-ends for C, C++, Objective-C, Fortran, etc. They support the ANSI-standard C and C++ languages. Additionally, many GCC extensions are supported.
- A stable implementation of the LLVM instruction set, which serves as both the online and offline code representation, together with assembly (ASCII) and bytecode (binary) readers and writers, and a verifier.
- A powerful pass-management system that automatically sequences passes (including analysis, transformation, and code-generation passes) based on their dependences, and pipelines them for efficiency.
- A wide range of global scalar optimizations.
- A link-time interprocedural optimization framework with a rich set of analyses and transformations, including sophisticated whole-program pointer analysis, call graph construction, and support for profile-guided optimizations.
- An easily retargetable code generator, which currently supports X86, X86-64, PowerPC, PowerPC-64, ARM, Thumb, SPARC, Alpha, CellSPU, MIPS, MSP430, SystemZ, WebAssembly and XCore.
- A Just-In-Time (JIT) code generation system, which currently supports X86, X86-64, ARM, AArch64, Mips, SystemZ, PowerPC, and PowerPC-64.
- Support for generating DWARF debugging information.
- A profiling system similar to gprof.
- A test framework with a number of benchmark codes and applications.
- APIs and debugging tools to simplify rapid development of LLVM components.

## Strengths of the LLVM System

1. LLVM uses a simple [low-level language](https://llvm.org/docs/LangRef.html) with strictly defined semantics.
1. It includes front-ends for C and C++. Front-ends for Java, Scheme, and other languages are in development.
1. It includes an aggressive optimizer, including scalar, interprocedural, profile-driven, and some simple loop optimizations.
1. It supports a [life-long compilation model](https://llvm.org/pubs/2004-01-30-CGO-LLVM.html), including link-time, install-time, run-time, and offline optimization.
1. LLVM has full support for [accurate garbage collection](https://llvm.org/docs/GarbageCollection.html).
1. The LLVM code generator is relatively easy to retarget, and makes use of a powerful target description language.
1. LLVM has extensive [documentation](https://llvm.org/docs/) and has hosted many [projects](https://llvm.org/project-with-llvm) of various sorts.
1. Many third-party users have claimed that LLVM is easy to work with and develop for. For example, the (now removed) Stacker front-end was written in 4 days by someone who started knowing nothing about LLVM. Additionally, LLVM has tools to make [development easier](https://llvm.org/docs/Bugpoint.html).
1. LLVM is under active development and is constantly being extended, enhanced and improved. See the status updates on the left bar to see the rate of development.
1. LLVM is freely available under an OSI-approved "Apache License Version 2.0" license.
1. LLVM is currently used by many commercial, non-profit or academic entities, who contribute many extensions and new features.

## LLVM Audience

LLVM can be used in many different kinds of projects. You might be interested in LLVM if you are:

- A compiler researcher interested in compile-time, link-time (interprocedural), and runtime transformations for C and C++ programs.
- A virtual machine researcher/developer interested in a portable, language-independent instruction set and compilation framework.
- An architecture researcher interested in compiler/hardware techniques.
- A security researcher interested in static analysis or instrumentation.
- An instructor or developer interested in a system for quick prototyping of compiler transformations.
- An end-user who wants to get better performance out of your code.

## Want to Know More?

You can [browse the documentation online](https://llvm.org/docs/), try [LLVM in your web browser](https://llvm.org/demo/index.cgi), or [download the source code](https://llvm.org/releases/index.html).
