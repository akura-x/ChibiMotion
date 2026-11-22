# 🦎 ChibiMotion

**让像素小人跟着鼠标轻轻晃动。**  
*A tiny animated pixel-character companion that follows your mouse on Windows.*

[📦 下载 / Downloads](https://github.com/akura-x/ChibiMotion/releases) · [🐛 反馈问题 / Report an issue](https://github.com/akura-x/ChibiMotion/issues)

> **v0.6.0 Beta 更新准备中 / Coming next:** 双小人自由摆放、各自独立摇晃，以及每次启动前的使用声明。查看 [v0.6 更新说明](RELEASE_NOTES_v0.6.0.md)。新版本须在 Releases 正式发布后才能下载。

> **v0.5.1 Beta · Windows 10/11 (64-bit) · 免费使用 / Free to use · 闭源发行 / Closed source**  
> 这是预览测试版本。正式下载文件以 [Releases](https://github.com/akura-x/ChibiMotion/releases) 页面实际发布的附件为准。

## ✨ 简介

**ChibiMotion** 是一款轻量级 Windows 桌面像素角色动画工具。角色跟随鼠标移动，身体和尾巴等附加部件可以产生惯性摇摆、弹性回弹，配合眨眼动画，为桌面增添一点生气。

本仓库用于发布**程序介绍、版本更新与 Windows 发行包**。公开发行版不提供 Python 源码或角色素材编辑功能。

## 🎮 主要功能

- **内置角色切换**：直接切换制作者预设的角色。
- **惯性与回弹**：调整晃动强度、最大摆角、回弹速度和阻尼。
- **独立部件动画**：已内置的尾巴及其他附加部件可使用自己的运动参数。
- **眨眼动画**：让角色更加生动。
- **托盘操作**：从 Windows 系统托盘切换角色、暂停或退出。
- **自动保存设置**：不同角色分别保存基础运动设置。
- **封闭角色配置**：公开版不支持新增、删除或导入角色，也不支持修改锚点、替换 PNG 或增加部件。

## 📥 下载和使用

1. 在 [Releases](https://github.com/akura-x/ChibiMotion/releases) 下载 `ChibiMotion_v0.5.1_Windows.zip`（以实际发布的版本为准）。
2. **完整解压** ZIP，不要在压缩包内直接运行。
3. 双击 `ChibiMotion.exe` 启动。
4. 双击系统托盘中的 ChibiMotion 图标进入基础设置；右键可切换角色、暂停、查看「关于 / 反馈 / 使用声明」或退出。

**系统要求：** Windows 10 / 11，64 位。不需要另外安装 Python。当前 Beta 尚未进行代码签名；如 Windows 弹出安全提示，请核实下载来源，不要为运行本软件关闭安全防护。

**本地数据位置：**
- 配置：`%APPDATA%\ChibiMotionRelease\preferences.json`
- 错误日志：`%APPDATA%\ChibiMotionRelease\errors.log`

程序不会自动上传这些文件。提交日志前请先检查是否包含个人文件路径等信息。

## 💬 问题反馈 / Contact

遇到 Bug、兼容性问题或有任何建议，可通过以下方式联系：

- **X (Twitter)：** [@arendellex1](https://x.com/arendellex1)
- **Bilibili：** 锦瑟君
- **GitHub：** [Issues](https://github.com/akura-x/ChibiMotion/issues)

反馈时建议附上 ChibiMotion 版本、Windows 版本、复现步骤，以及必要的截图或录屏。

**制作者 / Creator：リベール**

## 📄 使用与版权声明

- ChibiMotion 是独立制作的非官方桌面动画程序，与相关游戏、角色权利人或平台**没有官方关联**。
- 第三方角色名称、设计和形象的权利归各自权利人所有。软件免费提供并不代表取得了所有第三方素材的再分发授权。
- 请优先分享本仓库或官方 Release 链接，而不是来源不明或经过修改的可执行文件。请勿冒名发布或出售本发行包；相关权利及例外以适用法律和第三方许可证为准。
- 本软件按现状提供，测试版本可能有 Bug 或兼容性问题。任何免责范围均受适用法律限制。
- 本仓库**不是开源代码仓库**；没有向外公开授予 ChibiMotion 自有代码的开源许可证。第三方组件仍保留各自的许可条件。
- 软件使用 Python、PySide6/Qt 等第三方组件。最终分发应遵守适用许可证义务；如果发行附件中的第三方通知仍标明“模板”，则**不代表完成了法律或许可证合规审查**。
- 如果你是相关权利人并希望反馈素材或其他权利问题，请通过上面的联系方式联系。

---

## English

**ChibiMotion** is a small Windows pixel-character companion featuring mouse-following movement, spring-like body sway, blinking, and independently animated built-in accessories such as tails.

**Platform:** Windows 10/11, x64. **Distribution:** Free beta, binary-only, closed-source.

**Features:** Built-in character switching, customizable motion strength / tilt / spring speed / damping, per-character preferences, system-tray controls, and blinking. Public releases do **not** allow importing characters or images, adding parts, or editing anchors.

**Install:** Download the Windows ZIP from [Releases](https://github.com/akura-x/ChibiMotion/releases), extract it completely, and run `ChibiMotion.exe`. Python is not required.

**Support:** [@arendellex1 on X](https://x.com/arendellex1), Bilibili: 锦瑟君, or [GitHub Issues](https://github.com/akura-x/ChibiMotion/issues).

**Notice:** This is an unofficial independent project and is not endorsed by any game or character rights holder. Third-party character rights remain with their owners. The software is supplied as-is to the extent permitted by law. This repository distributes documentation and release binaries, **not ChibiMotion source code**. Third-party license obligations and asset permissions must be addressed before broad public redistribution.
