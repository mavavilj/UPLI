# UPLI
The Unified Programming Language Interpolator

# Licenses

All code is under LGPL-3.0-or-later.  
All text is under GFDL-1.3-or-later.

# Project Idea

We wish to add at least Python syntax to C/C++ so that C/C++ can be directly written using more productive syntaxes without using additional runtimes, FFIs, virtual machines etc. We aim to achieve this through some combination of static AST processing (libclang) prior to compiling and macros.

Our priorities are:

* Standard C/C++ and a standard compiler (likely clang)
* Few or none external libraries

Our inspirations are, for example:

* https://github.com/linuxdeepin/unilang (one language to rule them all with analysis)
* https://haxe.org/ (one language to rule them all)
* https://fusion-lang.org/ (one language to rule them all)
* https://cython.org/ (Python wants to have C)
* https://github.com/BowenFu/hspp (Haskell on C++)

We deviate from these by, for example:

* Not requiring a n+1th standard (a new language, a new tool, ...), but by combining existing n standards
* Still being standard C/C++
* Leaving GC optional

# Branches

`prototype` is for a pre-planning stage to figure out what needs to be achieved
