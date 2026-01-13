# 👨‍💻 xiaobili - 技术档案

<div align="center">

[![OpenWrt_Auto_Build](https://img.shields.io/badge/OpenWrt_Auto_Build-固件编译-32C955?style=for-the-badge&logo=openwrt)](https://github.com/xiaobili/OpenWrt_Auto_Build)
[![openlist_episode_rename](https://img.shields.io/badge/openlist_episode_rename-媒体管理-FF69B4?style=for-the-badge&logo=python)](https://github.com/xiaobili/openlist_episode_rename)
[![wallhaven_spider](https://img.shields.io/badge/wallhaven_spider-网络爬虫-4EC0E8?style=for-the-badge&logo=web-scraping)](https://github.com/xiaobili/wallhaven_spider)

</div>

---

## 📖 概述

**xiaobili** 是一位热衷于开发实用工具的开源开发者，专注于网络路由器固件、媒体管理工具和自动化脚本等领域。其项目展示了在嵌入式系统、Python开发和前端技术方面的深厚功底。

- **GitHub 用户名**: [xiaobili](https://github.com/xiaobili)
- **用户ID**: 25179891
- **活跃度**: 高度活跃（最新更新于 2026-01-13）
- **项目数量**: 6 个公开仓库

---

## 🚀 项目组合

### 🌐 OpenWrt_Auto_Build 
> **基于 Lean 源码的 OpenWrt 固件云编译项目**

[![GitHub stars](https://img.shields.io/github/stars/xiaobili/OpenWrt_Auto_Build.svg?style=social&label=Star)](https://github.com/xiaobili/OpenWrt_Auto_Build)

- **创建日期**: 2026-01-09
- **最近更新**: 2026-01-13
- **设备适配**: X86、R2C、R2S、R2S、R4S、R4SE、R5C、R5S、香橙派、树莓派等多种设备
- **核心特性**:
  - ✅ 每天定时自动编译，确保最新体验
  - ✅ 集成常用有线、无线、3G/4G 网卡驱动
  - ✅ 集成中文版 netdata 实时监控插件
  - ✅ 集成 iStore 应用商店，方便插件安装
  - ✅ 支持 Docker 服务，在 OpenWrt 内部署 Docker 应用
  - ✅ ARMv8 盒子固件分 Mini版（科学上网为主）和 Plus版（多功能版）

<details>
<summary>点击展开项目详情</summary>

该项目使用 GitHub Actions 拉取 Lean 的 Openwrt 源码仓库进行云编译，固件默认管理地址为 `192.168.1.1`，用户为 `root`，密码为 `password`。提供了适配于 ARMv8 电视盒子、Rockchip 平台、树莓派以及 X86 平台设备的 OpenWrt 固件。

</details>

### 📺 openlist_episode_rename
> **交互式剧集批量重命名工具**

[![GitHub stars](https://img.shields.io/github/stars/xiaobili/openlist_episode_rename.svg?style=social&label=Star)](https://github.com/xiaobili/openlist_episode_rename)

- **创建日期**: 2026-01-12
- **最近更新**: 2026-01-13
- **语言**: Python 3.7+
- **核心功能**:
  - ✅ 交互式导航 OpenList 文件系统
  - ✅ 支持多种重命名模式（智能识别、手动输入、统一样式等）
  - ✅ 自动从文件名中提取剧集信息
  - ✅ 提供美观的终端界面（Rich 版本）
  - ✅ 操作过程可视化进度条
  - ✅ 重命名前预览和确认机制

<details>
<summary>点击展开使用示例</summary>

支持的视频格式包括 `.mp4`, `.mkv`, `.avi`, `.mov`, `.wmv`, `.flv`, `.webm`, `.m4v`, `.mpg`, `.mpeg`, `.ts`, `.m2ts`, `.vob`, `.iso` 等。

命名模式示例：
- `{title}.S{season}E{episode:02d}` → `权力的游戏.S01E01.mp4`
- `Season_{season}_Episode_{episode:02d}_{title}` → `Season_01_Episode_01_权力的游戏.mp4`

</details>

### 🖼️ wallhaven_spider
> **wallhaven壁纸网站爬虫**

[![GitHub stars](https://img.shields.io/github/stars/xiaobili/wallhaven_spider.svg?style=social&label=Star)](https://github.com/xiaobili/wallhaven_spider)

- **创建日期**: 2023-10-11
- **技术栈**: Python, requests, pyppeteer, BeautifulSoup
- **跨平台支持**: Windows, Linux, macOS

### 💻 code-image
> **通过 RaySO 创建代码图像**

- **创建日期**: 2023-04-12
- **技术栈**: TypeScript, Node.js
- **功能**: 将剪贴板中的代码转换为图片并保存

---

## 🛠️ 技术专长

<div align="center">

| 领域 | 技术栈 | 熟练度 |
|------|--------|--------|
| **嵌入式系统** | OpenWrt, Linux | ⭐⭐⭐⭐⭐ |
| **Python开发** | 自动化脚本, API集成, 网络爬虫 | ⭐⭐⭐⭐⭐ |
| **前端开发** | Next.js, Web应用 | ⭐⭐⭐⭐ |
| **DevOps** | CI/CD, 自动化构建 | ⭐⭐⭐⭐ |
| **多媒体处理** | 文件管理和重命名 | ⭐⭐⭐⭐ |

</div>

---

## 📊 活跃统计

<div align="center">

![Profile View Counter](https://komarev.com/ghpvc/?username=xiaobili&color=blueviolet&style=flat-square)

</div>

- **最新贡献**: 2026年1月13日
- **主要活跃时段**: 2021年至今
- **项目维护**: 积极维护，持续更新
- **代码质量**: 项目文档齐全，用户体验良好

---

## 🎯 项目亮点

- 🔧 **实用导向**: 所有项目都针对实际问题，解决真实需求
- 📚 **文档完善**: 项目配有详细说明和使用指南
- 🚀 **自动化**: 专注自动化工具，提高工作效率
- 🌐 **兼容性**: 支持多平台，适配多种设备
- 💡 **创新性**: 结合新技术解决传统问题

---

## 🤝 联系方式

如对以上项目感兴趣，可前往 [xiaobili 的 GitHub 主页](https://github.com/xiaobili) 查看详细信息。

<div align="center">

**感谢您的访问！✨**

*享受技术带来的便利，创造更美好的数字生活*

</div>
