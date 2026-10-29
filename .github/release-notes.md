## 中文

**v0.5.23 · Android build 68**

### 更新

- 更新多语言 Remote 设置说明，明确支持通过端到端加密 P2P 网络访问 DeepSeek Harness、CodeX、Claude Code 和 Pi 工作区，覆盖桌面、网页、iOS 与 Android 客户端。
- 简化设置布局：移除 Server 地址，将账号授权说明与账号值放在同一行；保留 ACP 设置并移除无用的新增工作区入口。

### 修复

- 修复 Remote 面板打开后刷新和关闭按钮有时无法点击的问题。
- 默认开启 Remote Tools，并修复设置不可用时的 Host 发现。
- 加固大响应传输、搜索投影和连接生命周期的超时与大小边界。
- 修复 CodeX 会话模型元数据恢复，并稳定 HMR 重载期间的设置写入。

感谢择梦舟（@dreamfarer-space）的贡献。

## English

**v0.5.23 · Android build 68**

### Updates

- Refresh the multilingual Remote settings copy to describe end-to-end encrypted P2P access to DeepSeek Harness, Codex, Claude Code, and Pi workspaces across desktop, web, iOS, and Android.
- Simplify the settings layout by removing the Server address, keeping account authorization details together, retaining ACP settings, and removing the unused add-workspace entry.

### Fixes

- Fix Remote panel refresh and close actions being blocked after the panel opens.
- Enable Remote Tools by default, while preserving the setting to disable them and Host discovery when settings are unavailable.
- Harden deadlines and size limits for large responses, search projections, and connection lifecycle cleanup.
- Preserve CodeX session model metadata and stabilize settings writes during HMR reloads.

Thanks to 择梦舟 (@dreamfarer-space) for the contribution.
