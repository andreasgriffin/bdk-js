# Running BDK in a webbrowser





## Setup

You'll need `wasm-pack` and `wasm-bindgen` installed.

To build the project:

```
wasm-pack build --release --target web
```

To run the example:

```
npx http-server --cors -c-1 -p 8080 --mime-types '{"wasm": "application/wasm", "html": "text/html", "css": "text/css", "js": "text/javascript", "json": "application/json", "jpg": "image/jpeg", "png": "image/png", "gif": "image/gif", "mp3": "audio/mpeg", "ogg": "audio/ogg", "wav": "audio/wav", "mp4": "video/mp4", "webm": "video/webm"}'

```



