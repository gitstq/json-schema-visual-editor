# Contributing to JSON Schema Visual Editor

首先，感谢您对 JSON Schema Visual Editor 项目的关注！我们欢迎所有形式的贡献，包括但不限于 bug 报告、功能建议、代码贡献和文档改进。

## 如何贡献

### 报告 Bug

如果您发现了 bug，请通过 GitHub Issues 报告，并尽可能提供以下信息：

- 问题的简要描述
- 复现步骤
- 期望行为 vs 实际行为
- 浏览器版本和操作系统
- 控制台错误信息（如果有）

### 建议新功能

我们欢迎新功能建议！请通过 GitHub Issues 提交，并描述：

- 功能的使用场景
- 期望的行为
- 可能的实现方案（可选）

### 提交代码

1. Fork 本仓库
2. 创建您的功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

### 代码规范

- 保持代码简洁清晰
- 添加必要的注释
- 确保代码在不同浏览器中兼容
- 遵循现有的代码风格

## 开发环境

由于本项目是纯前端项目，无需复杂的构建步骤：

```bash
# 克隆仓库
git clone https://github.com/yourusername/json-schema-visual-editor.git

# 进入目录
cd json-schema-visual-editor

# 启动本地服务器
npm start
# 或
python3 -m http.server 8080

# 在浏览器中打开 http://localhost:8080
```

## 许可证

通过贡献代码，您同意您的贡献将在 MIT 许可证下发布。
