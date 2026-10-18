# 隐私说明 / Privacy

TabHop 是离线运行的 Windows 快捷键工具。它在内存中临时处理键盘事件，并读取当前前台窗口所属进程的文件名，以判断是否应用用户选择的快捷键规则。

- 不记录或上传输入的文字、按键历史、网页地址或浏览历史。
- 无账号、广告、遥测或应用自身的网络通信功能。
- 0.1 版内置 Chrome / Edge 的 Alt+1、Alt+2 规则；0.2 版新增规则配置，只在本机保存应用进程文件名、原快捷键、目标快捷键和启用状态。保存的是用户设置，不是输入记录。
- EXE 版配置存于当前用户的本地应用数据目录，开机启动选择存于当前用户注册表。EXE 卸载保留配置，用户可自行删除 `%LOCALAPPDATA%\TabHop`。
- MSIX 商店版使用 Windows 管理的 LocalState 目录和 StartupTask。卸载时按 Windows 的应用数据规则清理；商店下载、更新和账号服务由 Microsoft Store 提供。

TabHop processes keyboard events transiently in memory to apply per-application shortcut rules. It does not log typed text or keystroke history, transmit input, collect browsing history, or send telemetry. Version 0.2 stores only user-defined executable names, source/target shortcuts and enabled states locally. It has no accounts, ads or application networking. Packaged versions use Windows-managed local application storage and opt-in startup tasks.

## 第三方服务

GitHub 下载、发布页访问和问题反馈适用 [GitHub 隐私政策](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)。
Microsoft Store 分发、更新和账号服务适用 [Microsoft 隐私声明](https://privacy.microsoft.com/privacystatement)。

问题反馈可能公开显示。请勿提交密码、访问令牌、敏感输入内容或其他个人信息。
隐私问题可通过 [GitHub Issues](https://github.com/sunholdshen/tabhop/issues) 联系维护者。
