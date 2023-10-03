[https://openmc-data-storage.github.io/isotope_plotter.rs/](https://openmc-data-storage.github.io/isotope_plotter.rs/)

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