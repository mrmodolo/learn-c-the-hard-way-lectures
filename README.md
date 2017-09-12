Learn C The Hard Way, Lectures
==============================

This is a publicly accessible repository of code for readers of my book Learn C The Hard Way, including the lecture slides and code I create for each exericse and video.

Aqui vão minhas anotações e modificações durante a leitura do livro!

GDB debuger
===========

* gdbgui Browser-based frontend to gdb (gnu debugger). Add breakpoints, view the stack, visualize data structures, and more in C, C++, Go, Rust, and Fortran. Run gdbgui from the terminal and a new tab will open in your browser.
* https://github.com/cs01/gdbgui/
* Instalado e testado! Funciona bem!

Ferramentas para verificar código e memória
===========================================

Splint
------
* Splint is a tool for statically checking C programs for security vulnerabilities and coding mistakes. With minimal effort, Splint can be used as a better lint. If additional effort is invested adding annotations to programs, Splint can perform stronger checking than can be done by any standard lint.
* http://www.splint.org/
* db: Employee Database Program http://www.splint.org/samples/db/index.html
* Manual http://splint.org/manual/manual.html
* O problema é que Splint não suporta 100% do pardão ISO C99!

Addresssanitizer
----------------
* Addresssanitizer - (aka ASan) is a memory error detector for C/C++.
* https://github.com/google/sanitizers/wiki/AddressSanitizer

Valgring
--------
* Valgrind Valgrind is an instrumentation framework for building dynamic analysis tools. There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your programs in detail. You can also use Valgrind to build new tools.
* http://valgrind.org/

Understanding glibc malloc
==========================
https://sploitfun.wordpress.com/2015/02/10/understanding-glibc-malloc/
