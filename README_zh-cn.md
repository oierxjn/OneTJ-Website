# OneTJ 文档网站

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

[OneTJ](https://github.com/oierxjn/OneTJ)（同济大学学生服务客户端）的官方文档网站。

## 简介

OneTJ 是一款基于 Flutter 的移动应用，为同济大学学生提供简洁、专注的使用体验，支持查看学生个人信息与校历相关内容。

## 功能特性

- **统一认证** - 基于 OAuth 2.0 的同济大学统一身份认证系统，支持自动令牌刷新
- **信息中心** - 展示学生基本信息（姓名、学号、学院、年级等）
- **课表管理** - 获取并展示学生课程安排，支持按周次查看
- **校历服务** - 显示当前学期、周次等校历信息，帮助掌握学期进度
- **本地存储** - 使用 Hive 数据库安全缓存认证信息和用户数据
- **多语言** - 支持中英文双语界面切换

## 文档

本仓库包含 OneTJ 的文档源码，使用 [VitePress](https://vitepress.dev/) 构建，采用 [vitepress-theme-teek](https://teek.docsify.top/) 主题。

### 快速开始

```bash
# 安装依赖
pnpm install

# 启动开发服务器
pnpm docs:dev

# 构建生产版本
pnpm docs:build

# 预览生产构建
pnpm docs:preview
```

## 项目结构

```
OneTJ-Website/
├── docs/
│   ├── .vitepress/     # VitePress 配置
│   ├── @pages/         # 自定义页面
│   ├── public/         # 静态资源
│   └── index.md        # 首页
├── package.json
└── README.md
```

## 相关链接

- **GitHub 仓库**：[oierxjn/OneTJ](https://github.com/oierxjn/OneTJ)
- **原始仓库**：[FlowerBlackG/OneTJ](https://github.com/FlowerBlackG/OneTJ)
- **同济大学 API**：api.tongji.edu.cn

## 反馈交流

在使用过程中有任何问题和想法，请给我提 [Issue](https://github.com/oierxjn/OneTJ/issues)。

## 许可证

MIT
