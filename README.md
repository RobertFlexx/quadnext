# QuadNext

QuadNext is an enhanced fork of Miniquad, a lightweight,
cross-platform graphics and windowing library written in Rust.

Originally developed for Tankyard, QuadNext extends Miniquad
with additional rendering features, platform improvements,
and graphics backend optimizations.

## Features

- Lightweight graphics and windowing abstraction.
- OpenGL and Metal rendering backends.
- MetalFX spatial upscaling.
- External OpenGL texture interoperability.
- Improved Metal render targets and multisampling.
- Apple Silicon and macOS graphics optimizations.
- FreeBSD platform support.
- Improved texture filtering and GPU synchronization.

## Compatibility

QuadNext retains the `miniquad` Cargo package name and aims
to maintain compatibility with existing Miniquad and Macroquad
applications.

Additional platform and rendering features remain under
active development.

## Building

```sh
cargo build --release
```

Run an example:

```sh
cargo run --example quad
```

## Upstream

QuadNext is based on [Miniquad](https://github.com/not-fl3/miniquad).

The original upstream documentation is available in
[README.upstream.md](README.upstream.md).

## License

Licensed under either of the following, at your option:

- [MIT License](LICENSE-MIT)
- [Apache License, Version 2.0](LICENSE-APACHE)

Original upstream copyright and attribution are retained.
