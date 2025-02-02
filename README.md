### Hashtable in C
This repository is a minimal hashtable implementation in the C programming language in about ~200 lines of code.
It is based on [this](https://benhoyt.com/writings/hash-table-in-c/) article.
The release contains a `demo` file that executes a minimal proof of concept.

Key features of the implementation:
- uses FNV-1a hashing algorithm
- uses "linear probing" on collisions
- has 16 base capacity, upscales when 50% of the table is full
