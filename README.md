# Tauri + Vanilla

This template should help get you started developing with Tauri in vanilla HTML, CSS and Javascript.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## 下载安装

MacOS

下载后的dmg安装后，并不能打开会提示“已损坏，无法打开”，实际上是因为没签名导致的。

解决方法

```sh
codesign --force --deep --sign - /Applications/uiautodev.app
```

再次打开如果提示未信任，就去设置-隐私与安全性 点击 “仍要打开”