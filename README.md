# 知乎MCP热门内容汇总项目

## 项目简介

本项目使用 Playwright MCP 工具抓取知乎上关于 MCP（Model Context Protocol）的热门文章，并整理成结构化的 Markdown 文档。

## 项目结构

```
.
├── README.md                    # 项目说明文档
├── package.json                 # Node.js 项目配置
├── package-lock.json           # 依赖锁定文件
├── .gitignore                   # Git 忽略文件配置
└── Users/ruanbanqi/知乎MCP热门内容汇总.md  # 抓取的知乎内容汇总
```

## 功能特点

- 🔍 **智能搜索**: 通过百度搜索绕过知乎访问限制
- 📊 **内容整理**: 自动提取文章标题、发布时间和内容摘要
- 📝 **结构化输出**: 生成格式化的 Markdown 文档
- 🚫 **隐私保护**: .env 文件已被排除在版本控制之外

## 技术栈

- **Playwright MCP**: 用于网页自动化和内容抓取
- **Node.js**: 运行环境
- **Git**: 版本控制
- **GitHub**: 代码托管

## 使用方法

1. 克隆项目到本地
```bash
git clone https://github.com/bqzgsx/zhihu-mcp-content-summary.git
cd zhihu-mcp-content-summary
```

2. 安装依赖
```bash
npm install
```

3. 查看抓取结果
打开 `Users/ruanbanqi/知乎MCP热门内容汇总.md` 文件查看整理好的知乎内容。

## 抓取内容概览

本项目成功抓取了知乎上关于 MCP 的热门内容，包括：

- MCP 工具测评和对比
- MCP 部署和配置教程
- MCP 技术分析和应用案例
- MCP 生态系统发展趋势

## 注意事项

- 本项目仅用于学习和研究目的
- 请遵守相关网站的使用条款和 robots.txt 规则
- 抓取的内容版权归原作者所有

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！