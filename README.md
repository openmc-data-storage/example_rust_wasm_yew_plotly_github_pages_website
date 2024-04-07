This Yew based Rust WASM website is hosted here

[https://openmc-data-storage.github.io/example_rust_wasm_yew_plotly_github_pages_website/](https://openmc-data-storage.github.io/example_rust_wasm_yew_plotly_github_pages_website/)

<!-- To build locally
```
```

To host locally
```
python -m http.server 8000
``` -->

Install instructions on Ubuntu 22.04
```
sudo apt-get install curl
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
. "$HOME/.cargo/env"
rustup target add wasm32-unknown-unknown
cargo build --target wasm32-unknown-unknown --release
cargo install --locked trunk
trunk serve --open
```
