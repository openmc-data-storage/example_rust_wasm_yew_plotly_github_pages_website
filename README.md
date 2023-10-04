[https://openmc-data-storage.github.io/isotope_plotter.rs/](https://openmc-data-storage.github.io/isotope_plotter.rs/)

To build locally
```
cargo build --target wasm32-unknown-unknown --release

```

To host locally
```
python -m http.server 8000
``` 

to build and host
```
cargo install --locked trunk
trunk serve --open
```

Then copy the dist folder to the docs folder and commit to gh-pages branch