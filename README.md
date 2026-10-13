# ropedia desktop

这里发布 ropedia desktop 的安装包和更新说明。下载请前往 [Releases](https://github.com/Ropedia/ropedia-desktop-releases/releases)。

提供 macOS ARM64、Windows x64 和 Linux x86_64 安装包。首次下载最新安装包，旧安装版可覆盖安装。后续通过设置中的“应用更新”检查、下载并确认安装。Linux 下载后按包内 README 手动安装。

每个 Release 附 `update.json`、Ed25519 签名和 `SHA256SUMS.txt`。应用会验证发布签名和安装包哈希，安装前检查录制、导出和回放状态。源码在独立的私有仓库维护。
