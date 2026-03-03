# 🦀 Learning Rust

A comprehensive, chapter-by-chapter journey through [*The Rust Programming Language*](https://doc.rust-lang.org/book/) (2nd Edition) by Steve Klabnik and Carol Nichols — commonly known as "The Book" in the Rust community.

## About

This repository documents my hands-on progress learning Rust from the ground up. It contains exercises, chapter projects, and code experiments as I work through each section of the book. The goal is to build a strong systems programming foundation with Rust, focusing on memory safety, performance, and concurrency.

## Skills Developed

`Rust` · `Systems Programming` · `Memory Management` · `Ownership & Borrowing` · `Concurrency & Multithreading` · `Error Handling` · `CLI Development` · `Test-Driven Development` · `Generics & Traits` · `Smart Pointers` · `Functional Programming Patterns` · `Cargo & Crate Management`

## What the Book Covers

**Foundations** — Variables, mutability, data types, functions, control flow, and an introduction to Cargo and the Rust toolchain.

**Ownership** — Rust's ownership model, borrowing, references, and slices. The core mental model for how Rust achieves memory safety without garbage collection.

**Structuring Data** — Structs, enums, `Option<T>`, and pattern matching with `match`. How Rust encourages expressive, type-safe data modeling.

**Organizing Code** — Packages, crates, modules, and paths. How Rust projects scale from single files to multi-module libraries.

**Collections & Error Handling** — Vectors, strings, hash maps, and Rust's approach to errors through `Result<T, E>` and the `?` operator.

**Generics, Traits & Lifetimes** — Polymorphism in Rust. Writing generic code, defining shared behavior with traits, and lifetime annotations for reference validation.

**Testing** — Unit tests, integration tests, and test-driven development patterns in Rust.

**Building a CLI Tool** — A hands-on project building a `grep` clone (`minigrep`) that ties together file I/O, error handling, environment variables, and iterators.

**Functional Patterns** — Closures, iterators, and how Rust compiles high-level abstractions into zero-cost, performant machine code.

**Smart Pointers & Concurrency** — `Box<T>`, `Rc<T>`, `RefCell<T>`, threads, message passing with channels, and shared state with `Mutex<T>` and `Arc<T>`.

**Advanced Features** — Unsafe Rust, advanced trait usage, macros, and the type system's deeper capabilities.

**Final Project** — A multithreaded web server built from scratch, applying everything from the book into a single working system.

## Repository Structure

```
learning-rust/
├── ch01-getting-started/
├── ch02-guessing-game/
├── ch03-common-concepts/
├── ch04-ownership/
├── ch05-structs/
├── ch06-enums/
├── ch07-packages-crates/
├── ch08-collections/
├── ch09-error-handling/
├── ch10-generics-traits/
├── ch11-testing/
├── ch12-minigrep/
├── ch13-closures-iterators/
├── ch14-cargo-cratesio/
├── ch15-smart-pointers/
├── ch16-concurrency/
├── ch17-oop/
├── ch18-patterns/
├── ch19-advanced/
├── ch20-web-server/
└── experiments/
```

Directories are added as I reach each chapter.

## Resources

- [The Rust Programming Language (Book)](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rust Standard Library Docs](https://doc.rust-lang.org/std/)
- [Rustlings (Practice Exercises)](https://github.com/rust-lang/rustlings)
- [Rust Playground](https://play.rust-lang.org/)
