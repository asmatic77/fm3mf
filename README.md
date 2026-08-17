# three-mem-fast (I will most definitely change the name, I don't like it :P)

[![CI](https://github.com/asmatic77/three-mem-fast/actions/workflows/ci.yml/badge.svg)](https://github.com/asmatic77/three-mem-fast/actions/workflows/ci.yml)

## 3MF file reader in Rust.

Geared to be able to read very large 3MFs withouth eating unnecesary memory. The 3MF is readed using streaming parsing, to reduce memory footprint.
Other than that, the parser uses reasonable optimizations to read the file as fast as possible.

I don't aim (at least yet) to produce a full featured 3mf reader/writer.

| Spec | Read | Write |
|---|:---:|:---:|
| Core | Almost all | None |
| Production | None | None |

## On the use of AI for this repo

This repo is used as an exercise for learning Rust. The code is human written. The crates used, and the overall infrastructure is AI suggested but with many rounds of human iteration and refinement. Tests and benchmarks are generally AI-written.
