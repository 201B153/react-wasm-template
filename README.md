# React-WASM template

- This repo shows how to initiate the basic str app for react-wasm app.

# Installation

## Prerequisites

Upgrade npm, install Rust and wasm-pack(a one-stop shop for building and working with Rust-generated WebAssembly that you would like to interop with JavaScript).

```bash
npm install npm@latest -g
curl https://sh.rustup.rs -sSf | sh
curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
```

## To run locally

### Clone the repo

```bash
git clone https://github.com/201B153/react-wasm-template.git
```

### In `./wasm-lib`

```bash
cargo test
```

### Then in `Source-folder`

```bash
npm run build:wasm
```

and

```bash
npm install
```

### To run:

```bash
npm run start
```

## License

This project is licensed under [MIT](https://github.com/edwardwohaijun/image-editor/blob/master/LICENSE)
