# bevy-web-resizer

Automatically resize your Bevy app on the web (wasm) to the size of the browser window.

```rust
#[cfg(target_arch = "wasm32")]
{
    app.add_plugin(bevy_web_resizer::Plugin);
}
```

**⚠️ Note: this functionality is now [built into Bevy](https://github.com/bevyengine/bevy/commit/fed93a0edce9d66586dc70c1207a2092694b9a7d) and this crate will no longer be maintained.**

