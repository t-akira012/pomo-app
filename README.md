# Tauri + Vanilla TS

This template should help get you started developing with Tauri in vanilla HTML, CSS and Typescript.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## 概要

- tauri を利用して特定のURLを、常に最前面に表示するアプリ

## 仕様

- `./index.html` で `form` に入力したURLを `iframe` で `width: 100vw; height: 100vh;` で表示している

## Issue memo

- `pnpm tauri build` で `failed to bundle project: error running bundle_dmg.sh`
- `CI=true pnpm tauri build` で通る
- ref. [When running `tauri build`, `bundle_dmg.sh` errors `fails to bundle project` · Issue #3055 · tauri-apps/tauri](https://github.com/tauri-apps/tauri/issues/3055)
