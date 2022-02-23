# bevy-web-resizer

Automatically resize your Bevy app on the web (wasm) to the size of the browser window.

```rust
#[cfg(target_arch = "wasm32")]
{
    app.add_system(bevy_web_resizer::web_resize_system);
}
```

