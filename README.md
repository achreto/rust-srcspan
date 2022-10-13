# Source Span Library

This library provides a notion of a source spans for the [nom crate](https://docs.rs/nom/latest/nom/) that
facilitates keeping track of line and column numbers of the source file.


## License

see the LICENSE file.


## Authors

Reto Achermann


## Using SrcSpan

Simply add the srcspan library as one of the dependencies:

```
srcspan = { git = 'https://github.com/achreto/rust-srcspan' }
```

## Building

Building the library using the `cargo build` command:

```
$ cargo build
```

## Documentation

To build the documentation run the following command:

```
$ cargo doc --no-deps
```


## Contributing

Please follow the [naming and formatting conventions](https://doc.rust-lang.org/1.0.0/style/style/naming/README.html) of Rust.

Run `cargo fmt` before committing and ensure the tests are passing `cargo test`.