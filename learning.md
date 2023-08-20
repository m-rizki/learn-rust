# The Rust Programming Language

## Getting Started

- Installing Rust on Linux, macOS, and Windows
- Writing a program that prints Hello, world!
- Using cargo, Rust’s package manager and build system

### Installation

after installation : `rustc --version`

update : `rustup update`
uninstall rust & rustup : `rustup self uninstall`

### Local Documentation

`rustup doc`
<!-- issue on wsl
$ rustup doc
error: couldn't open browser: IO error: No such file or directory (os error 2)
-->

## Hello World

Running a Rust Program:

```bash
rustc main.rs # After compiling successfully, Rust outputs a binary executable.
./main
```

## Hello Cargo

Cargo is Rust’s build system and package manager.

creating new project

```bash
cargo new hello_cargo
# It has also initialized a new Git repository along with a .gitignore file. Git files won’t be generated if you run cargo new within an existing Git repository; 
# you can override this behavior by using cargo new --vcs=git.
cargo new --vcs=git

# see the available options
cargo new --help
```

### Cargo.toml

This file is in the TOML (Tom’s Obvious, Minimal Language) format, which is Cargo’s configuration format.

### Building and Running a Cargo Project

```bash
cargo build

# Cargo would have rebuilt the project before running it, and you would have seen the output
cargo run

# This command quickly checks your code to make sure it compiles but doesn’t produce an executable
cargo check
```

An additional advantage of using Cargo is that the commands are the same no matter which operating system you’re working on.

### Building for Release

```bash
cargo build --release
```
