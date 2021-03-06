# Rust MaxMind DB Reader #

[![Build Status](https://travis-ci.org/oschwald/maxminddb-rust.svg?branch=master)](https://travis-ci.org/oschwald/maxminddb-rust)

This library reads the MaxMind DB format, including the GeoIP2 and GeoLite2
databases.

## Rust Version Supported ##

This project supports Rust 1.0.0-beta.2.

## Building ##

To build everything:

```
make all check
```

## Usage ##

Add this to your `Cargo.toml`:

```toml
[dependencies]
maxminddb = "0.5.3"
```

and this to your crate root:

```rust
extern crate maxminddb;
```

## API Documentation ##

The API docs are on [GitHub Pages](http://oschwald.github.io/maxminddb-rust/maxminddb/struct.Reader.html).

## Example ##

See `example/lookup.rs` for a basic example.

## Contributing ##

Contributions welcome! Please fork the repository and open a pull request
with your changes.

## License ##

This is free software, licensed under the ISC license.

