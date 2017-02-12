# rtlsdr\_sys.rs -- Low-level bindings to `librtlsdr`

[Documentation](http://kchmck.github.io/doc/rtlsdr_sys/)

This crate provides low-level [FFI](https://doc.rust-lang.org/book/ffi.html) bindings
for [librtlsdr](https://git.osmocom.org/rtl-sdr/). See the
[`rtl-sdr.h`](https://git.osmocom.org/rtl-sdr/tree/include/rtl-sdr.h) header
distributed with the library for a description of each corresponding binding.

## Usage

This crate can be used through cargo by adding it as a dependency in `Cargo.toml`:

```toml
[dependencies]
rtlsdr_sys = {git = "https://github.com/kchmck/rtlsdr_sys.rs"}
```
and importing it in the crate root:

```rust
extern crate rtlsdr_sys;
```
