<div align="center">

# 🎨 JSON Schema Visual Editor

**A lightweight, browser-based JSON Schema visual editor with drag-and-drop interface, real-time preview, and multi-format export support.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/gitstq/json-schema-visual-editor?style=social)](https://github.com/gitstq/json-schema-visual-editor/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/gitstq/json-schema-visual-editor?style=social)](https://github.com/gitstq/json-schema-visual-editor/network/members)

[🌐 简体中文](#简体中文) | [🌐 繁體中文](#繁體中文) | [🌐 English](#english)

</div>

---

## 简体中文

### 🎉 项目介绍

JSON Schema Visual Editor 是一款**纯浏览器端运行**的 JSON Schema 可视化编辑器，无需任何后端服务或安装依赖。通过直观的拖拽界面，您可以快速设计和编辑 JSON Schema，实时预览生成的 Schema 和示例数据。

**灵感来源**：传统 JSON Schema 编辑工具要么过于复杂需要安装，要么功能简陋不够直观。本项目旨在提供一个**零依赖、开箱即用**的可视化解决方案。

### ✨ 核心特性

- 🎯 **零依赖** - 纯 HTML/CSS/JS 实现，无需 Node.js 或任何后端
- 🖱️ **拖拽编辑** - 直观的拖拽式属性添加，支持 6 种数据类型
- 👁️ **实时预览** - 实时生成 JSON Schema 和示例数据
- 📋 **一键复制** - 快速复制生成的 Schema 到剪贴板
- 📤 **导入导出** - 支持导入现有 Schema，导出为 JSON 文件
- ↩️ **撤销重做** - 完整的操作历史管理
- 🎨 **精美界面** - 现代化暗色主题设计
- 📱 **响应式布局** - 适配不同屏幕尺寸

### 🚀 快速开始

#### 环境要求

- 现代浏览器（Chrome、Firefox、Safari、Edge）
- 无需任何运行时依赖

#### 本地启动

```bash
# 克隆仓库
git clone https://github.com/gitstq/json-schema-visual-editor.git

# 进入目录
cd json-schema-visual-editor

# 启动本地服务器（任选一种方式）
# 方式1: Python
python3 -m http.server 8080

# 方式2: Node.js
npx serve .

# 方式3: PHP
php -S localhost:8080

# 在浏览器中打开 http://localhost:8080
```

#### 在线使用

直接打开 `index.html` 文件即可使用，无需服务器！

### 📖 详细使用指南

#### 基本操作

1. **添加属性**
   - 点击"添加属性"按钮
   - 或从左侧拖拽类型到画布

2. **编辑属性**
   - 点击属性右侧的 ✏️ 编辑按钮
   - 设置名称、类型、描述、约束条件

3. **删除属性**
   - 点击属性右侧的 🗑️ 删除按钮

4. **设置必填**
   - 在编辑属性时勾选"必填字段"

#### 支持的类型

| 类型 | 图标 | 说明 | 额外约束 |
|------|------|------|----------|
| String | 📝 | 字符串 | 最小/最大长度 |
| Number | 🔢 | 数字 | 最小/最大值 |
| Integer | #️⃣ | 整数 | 最小/最大值 |
| Boolean | ☑️ | 布尔值 | - |
| Array | 📚 | 数组 | - |
| Object | 📦 | 对象 | - |

#### 导入导出

- **导入**: 点击"导入"按钮，粘贴 JSON Schema
- **导出**: 点击"导出"按钮，下载为 `.json` 文件
- **复制**: 点击"复制 JSON"按钮，复制到剪贴板

### 💡 设计思路与迭代规划

#### 技术选型

- **纯原生技术栈**: HTML5 + CSS3 + Vanilla JavaScript
- **零构建工具**: 无需 Webpack、Vite 等构建工具
- **无框架依赖**: 不依赖 React、Vue 等前端框架

#### 设计原则

1. **简单至上** - 保持代码简洁，易于理解和修改
2. **开箱即用** - 下载即可使用，无需安装依赖
3. **功能完整** - 覆盖 JSON Schema 核心功能

#### 后续迭代计划

- [ ] 支持嵌套对象和数组的深层编辑
- [ ] 添加更多验证规则（正则、枚举等）
- [ ] 支持 JSON Schema  draft-07/2019-09 规范
- [ ] 添加主题切换功能
- [ ] 支持从 JSON 数据反向生成 Schema

### 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！请查看 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详情。

### 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

---

## 繁體中文

### 🎉 專案介紹

JSON Schema Visual Editor 是一款**純瀏覽器端運行**的 JSON Schema 可視化編輯器，無需任何後端服務或安裝依賴。通過直觀的拖拽介面，您可以快速設計和編輯 JSON Schema，即時預覽生成的 Schema 和範例資料。

### ✨ 核心特性

- 🎯 **零依賴** - 純 HTML/CSS/JS 實現，無需 Node.js 或任何後端
- 🖱️ **拖拽編輯** - 直觀的拖拽式屬性添加，支援 6 種資料類型
- 👁️ **即時預覽** - 即時生成 JSON Schema 和範例資料
- 📋 **一鍵複製** - 快速複製生成的 Schema 到剪貼簿
- 📤 **匯入匯出** - 支援匯入現有 Schema，匯出為 JSON 檔案
- ↩️ **復原重做** - 完整的操作歷史管理
- 🎨 **精美介面** - 現代化暗色主題設計
- 📱 **響應式佈局** - 適配不同螢幕尺寸

### 🚀 快速開始

#### 環境要求

- 現代瀏覽器（Chrome、Firefox、Safari、Edge）
- 無需任何執行時依賴

#### 本地啟動

```bash
# 克隆倉庫
git clone https://github.com/gitstq/json-schema-visual-editor.git

# 進入目錄
cd json-schema-visual-editor

# 啟動本地伺服器
python3 -m http.server 8080

# 在瀏覽器中開啟 http://localhost:8080
```

### 📖 詳細使用指南

#### 基本操作

1. **添加屬性** - 點擊"添加屬性"按鈕或從左側拖拽類型
2. **編輯屬性** - 點擊 ✏️ 編輯按鈕設定屬性詳情
3. **刪除屬性** - 點擊 🗑️ 刪除按鈕
4. **設定必填** - 在編輯屬性時勾選"必填欄位"

### 💡 設計思路

- **純原生技術棧**: HTML5 + CSS3 + Vanilla JavaScript
- **零構建工具**: 無需 Webpack、Vite 等構建工具
- **無框架依賴**: 不依賴 React、Vue 等前端框架

### 📄 開源協議

本專案採用 [MIT License](LICENSE) 開源協議。

---

## English

### 🎉 Introduction

JSON Schema Visual Editor is a **browser-based** visual editor for JSON Schema that requires no backend services or dependencies. With an intuitive drag-and-drop interface, you can quickly design and edit JSON Schemas with real-time preview of generated Schema and sample data.

**Inspiration**: Traditional JSON Schema editing tools are either too complex to install or too simplistic to be intuitive. This project aims to provide a **zero-dependency, ready-to-use** visual solution.

### ✨ Features

- 🎯 **Zero Dependencies** - Pure HTML/CSS/JS, no Node.js or backend required
- 🖱️ **Drag & Drop** - Intuitive drag-and-drop property addition with 6 data types
- 👁️ **Real-time Preview** - Live generation of JSON Schema and sample data
- 📋 **One-click Copy** - Quickly copy generated Schema to clipboard
- 📤 **Import & Export** - Import existing Schemas, export as JSON files
- ↩️ **Undo & Redo** - Complete operation history management
- 🎨 **Beautiful UI** - Modern dark theme design
- 📱 **Responsive Layout** - Adapts to different screen sizes

### 🚀 Quick Start

#### Requirements

- Modern browser (Chrome, Firefox, Safari, Edge)
- No runtime dependencies required

#### Local Development

```bash
# Clone repository
git clone https://github.com/gitstq/json-schema-visual-editor.git

# Enter directory
cd json-schema-visual-editor

# Start local server
python3 -m http.server 8080

# Open http://localhost:8080 in your browser
```

#### Online Usage

Simply open the `index.html` file - no server required!

### 📖 Usage Guide

#### Basic Operations

1. **Add Property** - Click "Add Property" button or drag types from sidebar
2. **Edit Property** - Click ✏️ edit button to configure property details
3. **Delete Property** - Click 🗑️ delete button
4. **Set Required** - Check "Required field" when editing property

#### Supported Types

| Type | Icon | Description | Constraints |
|------|------|-------------|-------------|
| String | 📝 | String value | Min/Max length |
| Number | 🔢 | Number value | Min/Max value |
| Integer | #️⃣ | Integer value | Min/Max value |
| Boolean | ☑️ | Boolean value | - |
| Array | 📚 | Array value | - |
| Object | 📦 | Object value | - |

### 💡 Design Philosophy

- **Pure Native Stack**: HTML5 + CSS3 + Vanilla JavaScript
- **Zero Build Tools**: No Webpack, Vite or other build tools needed
- **No Framework Dependencies**: No React, Vue or other frameworks

### 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

**Made with ❤️ by JSON Schema Visual Editor Team**

[⭐ Star this repo](https://github.com/gitstq/json-schema-visual-editor) | [🐛 Report Bug](https://github.com/gitstq/json-schema-visual-editor/issues) | [💡 Request Feature](https://github.com/gitstq/json-schema-visual-editor/issues)

</div>
