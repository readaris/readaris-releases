<div align="center">

# 📖 Readaris Multi-Platform Releases

**Read deeply. Understand more.**  
AI 驱动的西方哲学与英文经典深度精读平台 · 官方多平台客户端下载中心

[![Latest Release](https://img.shields.io/github/v/release/readaris/readaris-releases?color=blue&logo=github)](https://github.com/readaris/readaris-releases/releases/latest)
[![Release Downloads](https://img.shields.io/github/downloads/readaris/readaris-releases/total?color=success&logo=github)](https://github.com/readaris/readaris-releases/releases)
[![Platforms](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Android%20%7C%20iOS-brightgreen)](#-各平台下载)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Website-readaris.com-orange)](https://readaris.com/download)

[🌐 官方网站](https://readaris.com) • [📥 完整下载页](https://readaris.com/download) • [📝 更新日志](https://github.com/readaris/readaris-releases/releases) • [🐛 提交反馈 / 报告缺陷](https://github.com/readaris/readaris-releases/issues)

</div>

---

## 🌟 核心特性

- **双栏分级沉浸精读**：左侧经典英文原文对照，右侧高密学术解析与 Oxford 9 权威词典赋能。
- **思维模型与概念图谱**：深度拆解西方哲学核心脉络、论证结构与历史思想演进。
- **SRS 艾宾浩斯间隔复习**：结合真实语境例句的生词记忆流，摆脱死记硬背。
- **离线原本当地存储**：基于 Drift SQLite 本地持久化，无网络亦可毫秒级秒开调阅。
- **跨端无感云同步**：依托 Cloudflare 全球边缘网络，多设备阅读进度与书签毫秒级一致。

---

## 📦 各平台下载

> 💡 **提示**：如果在 GitHub 下载速度较慢，推荐访问官网获取全球 CDN 加速下载：[readaris.com/download](https://readaris.com/download)

| 操作系统 | 适用架构 / 格式 | 安装包类型 | 下载入口 |
| :--- | :--- | :--- | :--- |
| **macOS** | Apple Silicon (`arm64`) | `.dmg` 镜像文件 | [⬇️ 下载 (M1/M2/M3/M4 系列)](https://github.com/readaris/readaris-releases/releases/latest/download/Readaris-1.0.0-arm64.dmg) |
| **macOS** | Intel x86_64 (`x64`) | `.dmg` 镜像文件 | [⬇️ 下载 (Intel 处理器)](https://github.com/readaris/readaris-releases/releases/latest/download/Readaris-1.0.0-x64.dmg) |
| **Windows** | Windows 10 / 11 (64-bit) | `.exe` 安装程序 | [⬇️ 下载 64 位安装包](https://github.com/readaris/readaris-releases/releases/latest/download/Readaris-Setup-1.0.0-x64.exe) |
| **Windows** | Windows 10 / 11 (64-bit) | `.zip` 免安装绿色版 | [⬇️ 下载便携版 Zip](https://github.com/readaris/readaris-releases/releases/latest/download/Readaris-1.0.0-windows-portable.zip) |
| **Android** | Universal (全架构通用) | `.apk` 直装包 | [⬇️ 下载通用 APK](https://github.com/readaris/readaris-releases/releases/latest/download/Readaris-1.0.0-universal.apk) |
| **Android** | ARM64-v8a (轻量高效) | `.apk` 直装包 | [⬇️ 下载 ARM64 专版 APK](https://github.com/readaris/readaris-releases/releases/latest/download/Readaris-1.0.0-arm64-v8a.apk) |
| **iOS / iPadOS** | iPhone & iPad | App Store / TestFlight | [🍏 App Store 页面](https://apps.apple.com/app/readaris/id6470000000) · [✈️ TestFlight 公测版](https://testflight.apple.com/join/ReadarisBeta) |

---

## 🛠️ 各平台安装说明与故障排除

### 🍎 macOS
1. 下载 `.dmg` 文件后双击打开，将 **Readaris** 拖入 **Applications（应用程序）** 文件夹即可。
2. **若首次启动提示“无法打开，因为无法验证开发者”或“已损坏”**：
   - 方式一：在访达的「应用程序」中，**按住 Control 键并右键点击 Readaris**，在弹出菜单中点击「打开」。
   - 方式二：打开终端，执行以下命令移除 Apple 隔离属性：
     ```bash
     xattr -cr /Applications/Readaris.app
     ```

### 🪟 Windows
1. 运行 `Readaris-Setup-1.0.0-x64.exe` 按照向导完成安装；或解压便携包直接运行目录中的 `Readaris.exe`。
2. **首次运行弹出 Windows SmartScreen 提示“已保护你的电脑”**：
   - 这是因为应用尚未购买微软昂贵的商业 EV 证书，点击界面上的 **「更多信息 (More info)」**，然后点击 **「仍要运行 (Run anyway)」** 即可。

### 🤖 Android
1. 下载 `.apk` 文件并在手机浏览器或文件管理器中点击安装。
2. 若系统提示「禁止安装未知来源应用」，请在系统弹窗或权限设置中开启「允许来自此来源的安装」。

---

## 🔒 校验和验证 (SHA-256)

为保障您的设备安全，防止下载文件在网络传输中受损或被篡改，可对照 [Latest Release 页面](https://github.com/readaris/readaris-releases/releases/latest) 公布的哈希值核验：

```bash
# macOS / Linux
shasum -a 256 Readaris-1.0.0-arm64.dmg # SHA-256: 391c4fe1b65d065f4a6b076d1bda711f4f913e9cc595150633dd9ee54bedae96

# Windows (PowerShell)
Get-FileHash -Algorithm SHA256 .\Readaris-Setup-1.0.0-x64.exe
