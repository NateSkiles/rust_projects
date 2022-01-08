## Rust Notes

#### Getting Started 
Compiling Rust Code
* ```rustc```

Creating a new project using Cargo:
* ```cargo new```

**TOML**: _Tom's Obvious, Minimal Language_
* Cargo's configuration format.
* ```[package]```
* ```[dependencies]```

Building and Running a Cargo Project:
* ```cargo build``` creates an executable file in _/target/debug/.._
* ```cargo run``` compiles the code and runs the executable all in one command. Cargo finds out if the files have changed and if not only runs the executable - without recompiling.
* ```cargo check``` quickly checks code to make sure it complies but does **not** produce an executable

Releases
* ```cargo build --release``` complies the code with optimizations to make the Rust code run faster but lengthens the time it takes for your program to compline.



