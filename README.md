# Svelte-Rust-Wasm Template

Call Rust functions in Svelte web app via WebAssembly. The function would be available as node module with name provided by `package.name` in `Cargo.toml`.

## Requirements 
* Node.js stuff.
* Rust toolchain
* [`wasm-pack`](https://rustwasm.github.io/wasm-pack/installer/)

## Getting Started
1. clone this repo
2. `npm i`:this'll also triggers `prepare` script to build rust/wasm as local dependency first to `pkg` folder.
3. All other details can be read from `package.json`.

Note: `npm run dev` or `check:watch` wouldn't watch Rust source for changes, for now.