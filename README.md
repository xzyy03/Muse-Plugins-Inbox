# Muse 插件上传暂存区

Muse 客户端把插件包上传到这里，由 Muse-Plugins-Store 的 Actions 定时扫描、审计并合并进商店。

- incoming/ ：待审核的插件包，命名 <插件id>_<版本>.zip
- 审核通过后包会被复制进商店仓库，并出现在 App 的插件商店里
- 审核不通过会在同目录留下 .rejected.txt 说明原因

本仓库只作为暂存区，App 内置的写入凭据仅能提交到本仓库。
