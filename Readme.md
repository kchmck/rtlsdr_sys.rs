# rtlsdr\_sys.rs – Low-level bindings to `librtlsdr`

[Documentation](https://kchmck.github.io/doc/rtlsdr_sys/)

This crate provides low-level [FFI](https://doc.rust-lang.org/book/ffi.html) bindings
for [librtlsdr](https://git.osmocom.org/rtl-sdr/). See the
[`rtl-sdr.h`](https://git.osmocom.org/rtl-sdr/tree/include/rtl-sdr.h) header
distributed with the library for a description of each corresponding binding.

## Usage

This [crate](https://crates.io/crates/rtlsdr_sys) can be used through cargo by adding it
as a dependency in `Cargo.toml`:

```toml
[dependencies]
rtlsdr_sys = "1.1.0"
```
and importing it in the crate root:

```rust
extern crate rtlsdr_sys;
```
