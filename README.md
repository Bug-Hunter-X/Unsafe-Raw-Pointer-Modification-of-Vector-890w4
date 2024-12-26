# Unsafe Raw Pointer Modification of Vector in Rust

This repository demonstrates a potential issue with modifying a vector's elements through a raw pointer in Rust.  The code will likely panic because the pointer may become invalid if the vector's capacity changes.

The solution demonstrates a safer alternative using vector indexing.