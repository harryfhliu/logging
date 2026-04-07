# 穹顶洞察 · 测井行业技术情报站

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://logging.harryliu.cn)
[![Update](https://img.shields.io/badge/Update-Daily-blue)](https://logging.harryliu.cn)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.3-red)](https://jekyllrb.com/)

> 每日追踪全球石油测井领域前沿动态

## 🌐 在线访问

**主站地址：** [https://logging.harryliu.cn](https://logging.harryliu.cn)

## 📋 项目简介

本项目是一个专注于石油测井行业的技术情报分析平台，通过自动化系统每日追踪国内外测井领域的最新技术动态、市场趋势和行业突破，并以静态网站形式发布。

### 核心功能

- 📰 **每日简报**：工作日自动发布《测井行业要闻简报》
- 🔍 **技术追踪**：覆盖12个测井技术分类
- 📊 **数据存储**：SQLite数据库存储历史数据
- 📈 **趋势分析**：技术发展方向和市场热点分析
- 🔔 **RSS订阅**：支持RSS订阅更新

### 关注领域

| 分类 | 说明 |
|:---|:---|
| 🎯 随钻测井 | LWD/MWD随钻测量与测井技术 |
| 🔌 电缆测井 | Wireline电缆式测井技术 |
| 🔊 声波测井 | Acoustic Logging声波测井技术 |
| ⚛️ 核测井 | Nuclear Logging核测井技术 |
| 📷 成像测井 | Imaging Logging成像测井技术 |
| 🤖 智能测井 | AI/智能测井与数字化技术 |
| 🏭 生产测井 | Production Logging生产测井技术 |
| 🔍 套管检测 | Casing Inspection套管井检测技术 |
| 📊 地层评价 | Formation Evaluation地层评价技术 |
| 🔧 测井装备 | Logging Equipment测井装备与仪器 |
| 📈 行业动态 | Industry News行业动态与市场 |
| 🎓 学术会议 | Conferences学术会议与展览 |

## 🛠️ 技术栈

- **静态生成器**：Jekyll 4.3
- **主题风格**：深蓝科技风
- **托管平台**：GitHub Pages
- **自动化**：GitHub Actions
- **域名**：logging.harryliu.cn

## 📁 项目结构

```
.
├── _config.yml              # Jekyll 配置文件
├── _layouts/                # 页面布局模板
│   ├── default.html         # 基础布局
│   ├── post.html            # 文章详情页
│   └── page.html            # 通用页面
├── _includes/               # 可复用组件
├── _sass/                   # Sass 样式文件
├── assets/                  # 静态资源
│   ├── css/                 # 样式表
│   ├── js/                  # JavaScript
│   └── images/              # 图片资源
├── _posts/                  # 简报文章
│   └── 2025-04-07-logging-news.md
├── _pages/                  # 独立页面
│   ├── about.md             # 关于页面
│   ├── archive.html         # 归档页面
│   └── categories.html      # 分类页面
├── index.html               # 首页
├── CNAME                    # 域名配置
├── Gemfile                  # Ruby 依赖
└── .github/
    └── workflows/
        └── deploy.yml       # 自动部署工作流
```

## 🚀 本地开发

### 环境要求

- Ruby 2.7+
- Bundler

### 安装依赖

```bash
bundle install
```

### 本地预览

```bash
bundle exec jekyll serve
```

访问 http://localhost:4000 查看效果。

### 构建站点

```bash
bundle exec jekyll build
```

构建后的站点位于 `_site` 目录。

## 📝 添加新简报

1. 在 `_posts` 目录下创建新文件，文件名格式：`YYYY-MM-DD-logging-news.md`
2. 按照以下格式编写Front Matter：

```yaml
---
layout: post
title: "石油测井行业技术要闻简报"
date: 2025-04-07 09:30:00 +0800
categories: ["行业动态", "智能测井"]
tags: ["SLB", "自主测井"]
author: "穹顶洞察"
excerpt: "简报摘要..."
---
```

3. 提交并推送到 GitHub，自动触发部署

## 🔄 自动化流程

本项目通过 WorkBuddy 自动化任务系统实现每日简报自动生成：

1. **每日9:30** 自动搜索测井行业新闻
2. **分析整理** 提取关键信息并分类
3. **生成简报** 创建Markdown格式文章
4. **推送部署** 自动提交到GitHub并发布

## 📊 数据来源

- SLB官方网站
- 哈里伯顿官方网站
- 中国石油新闻中心
- 海默科技官网
- 新浪财经、澎湃新闻等主流媒体
- 《测井技术》等行业期刊
- SPWLA、OTC等国际会议

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进本项目。

## 📮 联系方式

- **GitHub Issues**：[harryfhliu/logging](https://github.com/harryfhliu/logging/issues)
- **RSS订阅**：[https://logging.harryliu.cn/feed.xml](https://logging.harryliu.cn/feed.xml)

---

<p align="center">
  <sub>由 <a href="https://github.com/harryfhliu">穹顶洞察</a> 维护 · 每日更新</sub>
</p>
