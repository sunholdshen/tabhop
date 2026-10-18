# TabHop

**用 Alt + 1 / Alt + 2，轻松切换 Chrome 和 Edge 标签页。**

免费的 Windows 托盘小工具，支持暂停、开机启动和一键退出。仅在浏览器为当前窗口时生效。

## 下载 v0.1.0-beta.1

| 电脑类型 | 下载 |
| --- | --- |
| 普通 Intel / AMD 电脑 | [Windows x64 安装包](https://github.com/sunholdshen/tabhop/releases/download/v0.1.0-beta.1/TabHop-0.1.0-beta.1-win-x64-Setup.exe) |
| Windows ARM 电脑 | [Windows ARM64 安装包](https://github.com/sunholdshen/tabhop/releases/download/v0.1.0-beta.1/TabHop-0.1.0-beta.1-win-arm64-Setup.exe) |

[查看版本说明和 SHA-256 校验文件](https://github.com/sunholdshen/tabhop/releases/tag/v0.1.0-beta.1)

需要 Windows 11 或 Windows 10 22H2，安装包已包含运行环境。此版本为 **Beta 测试版**，暂未代码签名，Windows 可能提示“未知发布者”。

## 使用

1. 安装并启动 TabHop，在右下角系统托盘找到蓝色双向箭头图标。
2. 打开 Chrome 或 Edge，在有多个标签页的窗口按 Alt+1 切左边标签、Alt+2 切右边标签。
3. 右键托盘可暂停、开启登录自启动或退出。其他应用保持原按键行为。

| 快捷键 | 操作 |
| --- | --- |
| Alt + 1 | 左边 / 上一个标签页 |
| Alt + 2 | 右边 / 下一个标签页 |

支持主键盘数字行；不映射小键盘、AltGr 或额外带 Ctrl/Shift/Win 的组合键。请以普通权限运行浏览器。

[完整使用说明](USER-GUIDE.md) · [隐私说明](PRIVACY.md) · [更新记录](CHANGELOG.md) · [反馈问题](https://github.com/sunholdshen/tabhop/issues/new/choose)

## 免费使用，源码不公开

允许个人和商业用途免费使用官方程序。TabHop 采用[专有软件许可](LICENSE)，此公开仓库仅用于产品介绍、下载和反馈。
Release 页面自动生成的 “Source code” 压缩包只包含本仓库的公开文档；请下载上面的 `.exe` 安装包。
第三方组件的许可保留在 [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt)。

## 隐私

TabHop 离线运行，不记录或上传键盘内容，不含遥测、广告或自动更新。
请从本仓库的 Releases 下载，并在需要时使用 SHA256SUMS.txt 核对文件。反馈问题时不要上传密码或其他敏感输入。

Copyright (c) 2026 sunholdshen. All rights reserved.
