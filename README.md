<div align="center">

**🌐 Language / 语言**

[English](#english) | [中文](#中文)

---

# 🗡️ Link Pet for Codex

**A brave chibi Link companion for your Codex terminal**

![Pet Preview](preview/contact-sheet.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Codex Pet](https://img.shields.io/badge/Codex-Pet-blue.svg)](https://github.com/openai/codex)

</div>

> **⚠️ Disclaimer / 免责声明**
>
> This is a **free, non-commercial fan project**. The Legend of Zelda and all related characters are trademarks of **Nintendo**. This project is not affiliated with, endorsed by, or sponsored by Nintendo in any way. No copyright infringement intended.
>
> 这是一个**免费的、非商业性质的粉丝项目**。《塞尔达传说》及相关角色是**任天堂**的商标。本项目与任天堂没有任何关联，也未获得任天堂的认可或赞助。无意侵犯版权。

---

<a id="english"></a>
## 🇬🇧 English

### Overview

A pixel-art Link pet sprite package for [OpenAI Codex](https://github.com/openai/codex). This chibi hero will accompany you during your coding adventures with 9 different animation states!

**This project is 100% free for personal use.**

### ✨ Features

| Animation | Frames | Description |
|-----------|--------|-------------|
| `idle` | 6 | Standing still, breathing animation |
| `running` | 6 | Running forward |
| `running-right` | 8 | Running to the right |
| `running-left` | 8 | Running to the left |
| `waving` | 4 | Waving hello |
| `jumping` | 5 | Jumping up |
| `failed` | 8 | Defeated animation |
| `waiting` | 6 | Waiting patiently |
| `review` | 6 | Reviewing code |

### 📦 Package Contents

```
link-pet-open-source/
├── pet.json              # Pet manifest (id, name, description)
├── spritesheet.webp      # Final spritesheet (1536×1872, WEBP RGBA)
├── README.md             # This file
├── preview/
│   └── contact-sheet.png # Animation preview image
├── extras/
│   └── spritesheet.png   # PNG version for editing
└── meta/
    ├── validation.json   # Atlas validation result
    └── review.json       # Frame extraction QA result
```

### 🚀 Installation

1. **Download** this repository:
   ```bash
   git clone https://github.com/MonaJTX/Codex-pets-link.git
   ```

2. **Copy** the pet folder to your Codex pets directory:
   ```bash
   # Linux/macOS
   cp -r Codex-pets-link ~/.codex/pets/link/

   # Windows (PowerShell)
   Copy-Item -Recurse Codex-pets-link $env:USERPROFILE\.codex\pets\link\
   ```

3. **Enjoy!** Link will appear in your Codex terminal.

### 📐 Technical Specs

| Property | Value |
|----------|-------|
| Spritesheet Size | 1536 × 1872 px |
| Frame Size | 192 × 208 px |
| Format | WEBP (RGBA) |
| Grid Layout | 8 columns × 9 rows |
| Total Frames | 57 |
| Status | ✅ All QA checks passed |

### 📝 License

MIT License - Free for personal, non-commercial use.

---

<a id="中文"></a>
## 🇨🇳 中文

### 概述

这是一个适用于 [OpenAI Codex](https://github.com/openai/codex) 的像素风格林克宠物精灵包。这个Q版小英雄将在你的编程冒险中陪伴你，拥有 9 种不同的动画状态！

**本项目 100% 免费，仅供个人使用。**

### ✨ 动画状态

| 动画 | 帧数 | 描述 |
|------|------|------|
| `idle` | 6 | 站立待机，呼吸动画 |
| `running` | 6 | 向前奔跑 |
| `running-right` | 8 | 向右跑 |
| `running-left` | 8 | 向左跑 |
| `waving` | 4 | 挥手打招呼 |
| `jumping` | 5 | 跳跃 |
| `failed` | 8 | 失败/被击败动画 |
| `waiting` | 6 | 耐心等待 |
| `review` | 6 | 代码审查 |

### 📦 包内容

```
link-pet-open-source/
├── pet.json              # 宠物清单（id、名称、描述）
├── spritesheet.webp      # 最终精灵图（1536×1872，WEBP RGBA）
├── README.md             # 本文件
├── preview/
│   └── contact-sheet.png # 动画预览图
├── extras/
│   └── spritesheet.png   # PNG版本，方便编辑
└── meta/
    ├── validation.json   # 图集验证结果
    └── review.json       # 帧提取QA结果
```

### 🚀 安装方法

1. **下载**本仓库：
   ```bash
   git clone https://github.com/MonaJTX/Codex-pets-link.git
   ```

2. **复制**宠物文件夹到 Codex 宠物目录：
   ```bash
   # Linux/macOS
   cp -r Codex-pets-link ~/.codex/pets/link/

   # Windows (PowerShell)
   Copy-Item -Recurse Codex-pets-link $env:USERPROFILE\.codex\pets\link\
   ```

3. **完成！** 林克将出现在你的 Codex 终端中。

### 📐 技术规格

| 属性 | 值 |
|------|-----|
| 精灵图尺寸 | 1536 × 1872 像素 |
| 单帧尺寸 | 192 × 208 像素 |
| 格式 | WEBP (RGBA) |
| 网格布局 | 8列 × 9行 |
| 总帧数 | 57 |
| 状态 | ✅ 所有QA检查通过 |

### 📝 许可证

MIT 许可证 - 免费供个人、非商业用途使用。

---

<div align="center">

### 🎮 Made with love for Codex

**Pet ID:** `link` | **Display Name:** 林克

![Spritesheet](extras/spritesheet.png)

⭐ If you like this pet, give it a star!

</div>
