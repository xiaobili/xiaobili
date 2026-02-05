# <img src="https://simpleicons.org/icons/github.svg" width="20" height="20" /> xiaobili - 技术档案

<div align="center">

[![OpenWrt_Action_Build](https://img.shields.io/badge/OpenWrt_Action_Build-固件编译-32C955?style=for-the-badge&logo=openwrt)](https://github.com/xiaobili/OpenWrt_Action_Build)
[![openlist_episode_rename](https://img.shields.io/badge/openlist_episode_rename-媒体管理-FF69B4?style=for-the-badge&logo=python)](https://github.com/xiaobili/openlist_episode_rename)
[![wallhaven_spider](https://img.shields.io/badge/wallhaven_spider-网络爬虫-4EC0E8?style=for-the-badge&logo=web-scraping)](https://github.com/xiaobili/wallhaven_spider)

</div>

---

## <img src="https://simpleicons.org/icons/readthedocs.svg" width="18" height="18" /> 概述

**xiaobili** 是一位热衷于开发实用工具的开源开发者，专注于网络路由器固件、媒体管理工具和自动化脚本等领域。其项目展示了在嵌入式系统、Python开发和前端技术方面的深厚功底。

- **GitHub 用户名**: [xiaobili](https://github.com/xiaobili)
- **用户ID**: 25179891
- **活跃度**: 高度活跃（最新更新于 2026-02-01）
- **项目数量**: 4 个公开仓库

---

## <img src="https://simpleicons.org/icons/rocket.svg" width="18" height="18" /> 项目组合

### <img src="https://simpleicons.org/icons/openwrt.svg" width="16" height="16" /> Openwrt_Action_Build 
> **OpenWrt 自动化构建，支持LEDE,ImmortalWrt**

[![GitHub stars](https://img.shields.io/github/stars/xiaobili/Openwrt_Action_Build.svg?style=social&label=Star)](https://github.com/xiaobili/Openwrt_Action_Build)

- **创建日期**: 2026-01-29
- **最近更新**: 2026-02-01
- **技术特点**:
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 支持 LEDE 和 ImmortalWrt 两个源码分支
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 提供完整版和迷你版两种固件构建选项
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 集成 GitHub Actions 实现自动化构建流程
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 支持定时构建和手动触发构建
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 包含 PassWall、AdGuard Home 等多种常用插件
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 预装 Argon 主题并优化界面体验

<details>
<summary>点击展开项目详情</summary>

该项目支持一键编译 OpenWrt 固件，具有丰富的插件和功能，包括 OpenAppFilter、Openlist、NetSpeedTest 等系统插件，以及 AdGuard Home、MosDNS 等网络工具。项目还提供了多种配置文件，可以满足不同的使用需求。

</details>

### <img src="https://simpleicons.org/icons/python.svg" width="16" height="16" /> openlist_episode_rename
> **交互式剧集批量重命名工具**

[![GitHub stars](https://img.shields.io/github/stars/xiaobili/openlist_episode_rename.svg?style=social&label=Star)](https://github.com/xiaobili/openlist_episode_rename)

- **创建日期**: 2026-01-12
- **最近更新**: 2026-01-30
- **语言**: Python 3.7+
- **核心功能**:
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 交互式导航 OpenList 文件系统
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 支持多种重命名模式（智能识别、手动输入、统一样式等）
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 自动从文件名中提取剧集信息
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 提供美观的终端界面（Rich 版本）
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 操作过程可视化进度条
  - <img src="https://simpleicons.org/icons/python.svg" width="12" height="12" /> 重命名前预览和确认机制

<details>
<summary>点击展开使用示例</summary>

支持的视频格式包括 `.mp4`, `.mkv`, `.avi`, `.mov`, `.wmv`, `.flv`, `.webm`, `.m4v`, `.mpg`, `.mpeg`, `.ts`, `.m2ts`, `.vob`, `.iso` 等。

命名模式示例：
- `{title}.S{season}E{episode:02d}` → `权力的游戏.S01E01.mp4`
- `Season_{season}_Episode_{episode:02d}_{title}` → `Season_01_Episode_01_权力的游戏.mp4`

</details>

### <img src="https://simpleicons.org/icons/python.svg" width="16" height="16" /> wallhaven_spider
> **wallhaven壁纸网站爬虫**

[![GitHub stars](https://img.shields.io/github/stars/xiaobili/wallhaven_spider.svg?style=social&label=Star)](https://github.com/xiaobili/wallhaven_spider)

- **创建日期**: 2023-10-11
- **最近更新**: 2026-01-15
- **技术栈**: Python, requests, pyppeteer, BeautifulSoup
- **跨平台支持**: Windows, Linux, macOS

### <img src="https://simpleicons.org/icons/python.svg" width="16" height="16" /> code-image
> **通过 RaySO 创建代码图像**

- **创建日期**: 2023-04-12
- **技术栈**: TypeScript, Node.js
- **功能**: 将剪贴板中的代码转换为图片并保存

---

## <img src="https://simpleicons.org/icons/python.svg" width="18" height="18" /> 技术专长

<div align="center">

| 领域           | 技术栈                        | 熟练度 |
| -------------- | ----------------------------- | ------ |
| **嵌入式系统** | OpenWrt, Linux                | <img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" />  |
| **Python开发** | 自动化脚本, API集成, 网络爬虫 | <img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" />  |
| **前端开发**   | Next.js, Web应用              | <img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" />   |
| **DevOps**     | CI/CD, 自动化构建             | <img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" />   |
| **多媒体处理** | 文件管理和重命名              | <img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" /><img src="https://simpleicons.org/icons/github.svg" width="12" height="12" />   |

</div>

---

## <img src="https://simpleicons.org/icons/target.svg" width="18" height="18" /> 活跃统计

<div align="center">

![Profile View Counter](https://komarev.com/ghpvc/?username=xiaobili&color=blueviolet&style=flat-square)

</div>

- **最新贡献**: 2026年2月1日
- **主要活跃时段**: 2021年至今
- **项目维护**: 积极维护，持续更新
- **代码质量**: 项目文档齐全，用户体验良好

---

## <img src="https://simpleicons.org/icons/target.svg" width="18" height="18" /> 项目亮点

- <img src="https://simpleicons.org/icons/python.svg" width="14" height="14" /> **实用导向**: 所有项目都针对实际问题，解决真实需求
- <img src="https://simpleicons.org/icons/readthedocs.svg" width="14" height="14" /> **文档完善**: 项目配有详细说明和使用指南
- <img src="https://simpleicons.org/icons/rocket.svg" width="14" height="14" /> **自动化**: 专注自动化工具，提高工作效率
- <img src="https://simpleicons.org/icons/openwrt.svg" width="14" height="14" /> **兼容性**: 支持多平台，适配多种设备
- <img src="https://simpleicons.org/icons/python.svg" width="14" height="14" /> **创新性**: 结合新技术解决传统问题

---

## <img src="https://simpleicons.org/icons/handshake.svg" width="18" height="18" /> 联系方式

如对以上项目感兴趣，可前往 [xiaobili 的 GitHub 主页](https://github.com/xiaobili) 查看详细信息。

<div align="center">

**感谢您的访问！<img src="https://simpleicons.org/icons/github.svg" width="14" height="14" />**

*享受技术带来的便利，创造更美好的数字生活*

</div>