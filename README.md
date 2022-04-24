# ActionKV [![Build](https://github.com/leonardovee/action-kv/actions/workflows/rust.yml/badge.svg)](https://github.com/leonardovee/action-kv/actions/workflows/rust.yml)

A key-value store, actionkv, stores and retrieves sequences of bytes of arbitrary length. 

Log-structured, append-only database systems, like this one, are significant as case studies because these are designed to be extremely resilient while offering optimal read performance.

Project created while studying the book [Rust in Action](https://github.com/rust-in-action)

## Usage

Execute the code passing the following arguments:

```
$ cargo run {FILE_NAME} get {KEY}
$ cargo run {FILE_NAME} delete {KEY}
$ cargo run {FILE_NAME} insert {KEY} {VALUE}
$ cargo run {FILE_NAME} update {KEY} {VALUE}
```

Example:

```
$ cargo run misc.val insert 1 {"message":"any message"}
```
## References

[Rust in Action - Systems programming concepts and techniques](https://www.manning.com/books/rust-in-action)
