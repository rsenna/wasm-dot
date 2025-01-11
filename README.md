# wasm-dot

Demo application of a simple wasm app in Rust.

> ℹ️ This is a **fork** of an original, currently unmaintained work
>
> Repo:  [wasm-dot](https://github.com/deciduously/wasm-dot)</br>
> Author: [Ben Lovy](https://github.com/deciduously).
>
> It's a simple demo of a resizable circle drawn on a HTML5 canvas, using Rust and WebAssembly, with a slider to control its size.
> 
> You can read the original author's post [here](post.md) or [online](https://dev.to/deciduously/reactive-canvas-with-rust-webassembly-and-web-sys-2hg2).
>
> Improvements:
> - Upgraded web dependencies
> - Now using [Cargo Make](https://sagiegurari.github.io/cargo-make/#usage-env) for convenience

## Usage

```bash
# Install cargo-make, if you don't already have it
$ cargo install --force cargo-make

# Clone the repo
$ git clone git@github.com:rsenna/wasm-dot.git

# Build and run the web app
$ cd wasm-dot
$ cargo make serve
```

Now open your web browser to <http://localhost:8080>, and play with your brand new dot!
