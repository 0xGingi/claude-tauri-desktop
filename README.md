# Claude Tauri Desktop

A desktop application for [Claude](https://claude.ai) built with Tauri.

I've made this because Claude does not have a Linux Desktop Client yet, and the projects that are maintaining them (rebuilds from the windows application) currently have broken titlebars, and I don't need MCP. So using this for now.

## Install

### Binaries (DEB,RPM,AppImage)

Download from https://github.com/0xGingi/claude-tauri-desktop/releases/latest

### Arch Linux (AUR)

AUR Package: https://aur.archlinux.org/packages/claude-tauri-desktop-git

## Build

### Prerequisites

- [Rust](https://www.rust-lang.org/)
- [Bun](https://bun.sh/)

### Building

```bash
bun install

bun run tauri build --bundles
```

This will build to `src-tauri/target/release/bundle`.
