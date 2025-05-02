# Operating Systems Reading List

This reading list concerns all things operating systems. Doubtless, there are more dedicated reading lists for many of these topics, which we should link once we find them. As we get more readings, we can extend the list of topics as required.

## Resource Management

- [Extending the Slab Allocator to Many Cores](./assets/slab_allocator_extension.md) Bondwick J., Adams J.. This paper deals with extending the slab allocator to solve two problems: 1) Global locking not scaling to many CPU systems and 2) Failure to manage resources other than kernel memory. [BibLaTex](./assets/slab_allocator_extension.bib).
- [Understanding Large Pages](https://web.archive.org/web/20250502185217/https://www.hudsonrivertrading.com/hrtbeat/low-latency-optimization-part-1/) - A discussion on using large pages optimally in low-level code. Crossreferenced in programming.

## Scheduling
- [A Decade of Wasted Cores](./assets/linux_scheduler.pdf) Lozi J. et al.. A paper detailing improvements to the linux scheduler that increase its ability to manage resources for many-core linux systems. [BibLaTex](./assets/linux_scheduler.bib).
