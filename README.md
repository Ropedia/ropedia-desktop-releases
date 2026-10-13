# ropedia desktop

这里发布 ropedia desktop 的安装包和更新说明。下载请前往 [Releases](https://github.com/Ropedia/ropedia-desktop-releases/releases)。

提供 macOS ARM64、Windows x64 和 Linux x86_64 安装包。`1.0.0` 开始支持应用内检查更新，旧版 `0.6.x` 首次需要手动安装新版。Linux 下载校验后按包内 README 手动安装。

每个 Release 附 `update.json`、Ed25519 签名和 `SHA256SUMS.txt`。应用会验证发布签名和安装包哈希，安装前检查录制、导出和回放状态。源码在独立的私有仓库维护。
