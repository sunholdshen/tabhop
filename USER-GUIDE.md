# TabHop 0.1.0-beta.1 使用说明

TabHop 是免费的闭源 Windows 托盘工具，用 Alt+1 / Alt+2 切换 Chrome 和 Edge 标签页。

## 下载

- Intel / AMD 电脑：[x64 安装包](https://github.com/sunholdshen/tabhop/releases/download/v0.1.0-beta.1/TabHop-0.1.0-beta.1-win-x64-Setup.exe)
- Windows ARM 电脑：[ARM64 安装包](https://github.com/sunholdshen/tabhop/releases/download/v0.1.0-beta.1/TabHop-0.1.0-beta.1-win-arm64-Setup.exe)
- [版本说明与校验文件](https://github.com/sunholdshen/tabhop/releases/tag/v0.1.0-beta.1)

目标系统为 Windows 11 或 Windows 10 22H2（19045），不支持 32 位系统。安装包自带运行环境。

## 安装与使用

1. 下载与电脑架构匹配的安装包并运行，阅读免费使用许可。
2. 如需登录 Windows 后自动启动，在组件页面勾选“开机启动”。默认关闭，稍后也可从托盘开启。
3. 完成安装并启动。蓝色双向箭头图标出现在系统托盘，也可能在右下角 `^` 隐藏图标区。
4. 让 Chrome 或 Edge 成为当前窗口，打开多个标签页后使用下面的快捷键。

| 按键 | 操作 |
| --- | --- |
| Alt + 1 | 切换到左边 / 上一个标签页 |
| Alt + 2 | 切换到右边 / 下一个标签页 |

支持主键盘数字行、左右 Alt；AltGr、Ctrl/Shift/Win 附加组合键和小键盘不参与映射。
按住 Alt 连续点数字可连续切换，长按数字遵循系统按键重复速度。标签首尾循环遵循浏览器自身行为。

其他应用不启用映射，也不会唤起后台浏览器。没有标签栏的浏览器弹窗或 PWA 可能没有切换效果。

## 托盘与开机启动

右键图标可启用/暂停快捷键、设置开机启动、查看说明或退出。双击图标打开说明。
退出后立即恢复原键盘行为。暂停只对本次运行有效，下次启动默认启用。
重复启动不会创建多个实例。开机启动只针对当前用户登录后的桌面会话。
如果在 Windows 设置或任务管理器里禁用了启动项，需要在那里重新启用。

## 卸载

从 Windows“设置 → 应用 → 已安装的应用”卸载 TabHop，或运行安装目录中的 Uninstall.exe。
默认安装目录为 `%LOCALAPPDATA%\Programs\TabHop`。卸载会移除应用、快捷方式和开机启动项。

## 测试版说明

这是首个公开测试版。用户已反馈此前版本在 Windows 实测可用；新版下载与安装体验正在验证。
目前没有代码签名，Windows 可能显示“未知发布者”或信誉提示。请核对官方发布地址和 SHA-256；不要关闭系统安全保护。

请让浏览器以普通用户权限运行。Windows 权限限制可能阻止普通程序向管理员浏览器发送按键；发送失败时程序暂停并提示。

## 隐私、许可与反馈

程序离线运行，不记录或上传键盘内容，没有遥测、广告或自动更新。下载和问题反馈使用 GitHub 服务。
允许个人和商业用途免费使用；源码不公开。具体许可见 LICENSE.txt，第三方许可见 THIRD-PARTY-NOTICES.txt。

反馈地址：https://github.com/sunholdshen/tabhop/issues
请提供系统/CPU 架构、浏览器版本、复现步骤和期望结果，不要附上密码、浏览内容或其他敏感信息。
