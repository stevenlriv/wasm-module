
# Simple WASM Module

## Installation

```bash
  cargo install wasm-pack
```
    
## Compile

```bash
  wasm-pack build --target web
```

## Appendix

- Setting crate-type to `["cdylib"]` is important because it tells Cargo to produce a dynamic system library, which is what you need for a WASM build.
- See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html
- Install rust here: https://rustup.rs