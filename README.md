# Running BDK in a webbrowser





## Setup

You'll need `wasm-pack` and `wasm-bindgen` installed.

To build the project:

```
wasm-pack build --target bundler --out-dir dist
```

To run the example:

```
npx http-server --cors -c-1 -p 8080 --mime-types '{"wasm": "application/wasm"}'
```



