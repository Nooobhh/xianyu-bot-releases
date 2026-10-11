# xianyu-bot-releases

xianyu-bot Mac 应用的安装包发布处，源码不在这里。

- 下载：[最新 Release](../../releases/latest) 里的 `xianyu-bot_<版本>_universal.dmg`（Apple Silicon / Intel 通用）
- 安装：把应用拖进「应用程序」；没做 Apple 公证，第一次打开要右键 → 打开
- 更新：已装的应用会自己检查新版本（读最新 Release 的 `latest.json`），弹窗里点「立即更新」

构建由源码仓库推 `v*` tag 触发（`repository_dispatch`），流程见 `.github/workflows/release.yml`。
