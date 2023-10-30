This is a template of nextjs(ts enabled) over Tauri. Before you work on this, change `name` in `package.json`, `package.projectName` and `tauri.bundle.identifier` in `src-tauri/tauri.conf.json` and `package.name` in `src-tauri/Cargo.toml`



To run dev, run

```shell
cargo tauri dev
```

To build and get a bundled installer, run

```shell
cargo tauri build
```

