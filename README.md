This Yew based Rust WASM website is hosted here

[https://openmc-data-storage.github.io/example_rust_wasm_yew_plotly_github_pages_website/](https://openmc-data-storage.github.io/example_rust_wasm_yew_plotly_github_pages_website/)

<!-- To build locally
```
```

To host locally
```
python -m http.server 8000
``` -->

```
cargo build --target wasm32-unknown-unknown --release
cargo install --locked trunk
trunk serve --open
```
