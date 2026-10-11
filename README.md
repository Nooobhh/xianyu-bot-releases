# xianyu-bot-releases

xianyu-bot 的构建产物（源码仓库私有）。那边推 `v*` tag 会触发这里的 workflow：构建、签名，然后发布 Release。

从 [Releases](https://github.com/Nooobhh/xianyu-bot-releases/releases/latest) 下载最新版：

- macOS（Apple Silicon / Intel 通用）：[`xianyu-bot-macos-universal.dmg`](https://github.com/Nooobhh/xianyu-bot-releases/releases/latest/download/xianyu-bot-macos-universal.dmg)

## 安装

打开 dmg，把 xianyu-bot 拖进「应用程序」。应用没做 Apple 签名公证，第一次要在 Finder 里**右键 → 打开**。

要在「应用程序」里运行：直接从 dmg 里打开的没法自动更新。

## 更新

应用启动后和之后每 6 小时检查一次新版本（读最新 Release 的 `latest.json`）。有新版会弹窗显示更新内容，点「立即更新」就下载、校验签名、自动重启；也可以跳过这个版本，之后想装时点顶栏的「更新」。
