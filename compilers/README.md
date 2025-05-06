# Compilers Reading List

A discussion of topics on the subject of compilers and programming languages more generally. Naturally there are other reading lists for many of these topics, if you find one you should link it! The main focuses of this particular list are:
- Front-end language development and analysis
- Middle-end machine-independent optimizations
- Back-end machine-dependent optimizations
- Code generation
- JIT compilers
- Non-compiled programming languages and utilities
    - Garbage collection
    - Efficient interpreters

As we gain more resources we can expand that list.

## Additional Reading Lists
- [CDOL Reading List](https://jnamaral.github.io/CDOL/) - J. Nelson Amaral's Lab reading list, covers a number of topics ranging from classic optimization passes to code placement optimization to code analysis and working with that information.
- [Compiler language books](https://github.com/rambhawan/Computer-Compiler-Lang/tree/master) - A collection of more books to complete your understanding not only of compilers, but of the fundamental logical structures that underpin them.

## Books
- [Crafting Interpreters](https://github.com/munificent/craftinginterpreters) - An excellent introduction to the design of computer languages, part 1 crafts an interpreter from scratch and part 2 a compiler. Highly encourage this as your starting point.
- [Compiler Construction](https://link.springer.com/book/10.1007/978-3-031-84813-1) - A recently published book on building a compiler for micro-java. No artifact for copyright purposes (but accessible through the U of A).
- [Introduction to Compilers and Language Design](./assets/intro_to_compiler_design.pdf) - A less recently published introductory text on building compilers and designing a language, focus on front-end.
- [Compilers: Principles, Techniques and Tools](./assets/dragon_book.pdf) - The dragon book. This book focuses more heavily on optimizations and dataflow than the other books. Note that most of the tools presented here already exist in LLVM.
- [Compiler Design Implementation](./assets/compiler_design_implementatino.pdf) - A book discussion proper implementation of a compiler.

## Garbage Collection
- [A Unified Garbage Collection](./assets/unified_garbage_collection.pdf) Bacon D., Cheng P., Rajan, V.. - Presents two algorithms treating garbage collection (tracing and reference counting) and shows that all high-performance garbage collectors can be expressed in terms of those algorithms. [BibLaTex](./assets/unified_garbage_collection.bib).
