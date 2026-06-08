<div align="center">

# 🍠 XHS — 小红书全栈运营助手

**一站式小红书运营 Claude Code Skill**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-2.0-green.svg)](CHANGELOG.md)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-purple.svg)](https://claude.ai/code)
[![Commands](https://img.shields.io/badge/Commands-20-orange.svg)](#-命令总览)

*从零起号到变现全流程，20 个子命令覆盖内容策划、竞品分析、视频脚本、SEO优化、变现规划...*

[快速开始](#-快速开始) · [命令总览](#-命令总览) · [文档](#-文档) · [贡献](#-贡献)

</div>

---

## ✨ 功能特性

| 能力 | 说明 |
|------|------|
| 📝 **内容生成** | 一键生成内容计划、爆款笔记、标题、视频脚本 |
| 🔍 **竞品分析** | 深度拆解竞品账号，找到差异化机会 |
| 📹 **视频脚本** | 生成完整视频脚本 + 分镜 + 配音文案 |
| 🔍 **SEO优化** | 关键词挖掘 + 标题优化 + 标签策略 |
| 💬 **评论运营** | 高情商回复模板，提升互动率 |
| 💰 **变现规划** | 按粉丝量规划变现路径 |
| 🏥 **账号诊断** | 5 维度全面诊断，找到瓶颈 |
| 🧑‍💼 **人设打造** | 语言/视觉/内容风格一体化指南 |
| 📅 **内容日历** | 月度排期 + 节日热点标注 |
| 🎯 **阶段指引** | 0 粉到 10 万粉分阶段指导 |

---

## 🚀 快速开始

### 安装

#### 方式一：手动安装

```bash
# 1. 克隆仓库
git clone https://github.com/moc81966-maker/xhs-skill.git

# 2. 复制到 Claude Code skills 目录
cp xhs-skill/SKILL.md ~/.claude/skills/xhs/SKILL.md
```

#### 方式二：直接下载

1. 下载 [`SKILL.md`](SKILL.md)
2. 放到 `~/.claude/skills/xhs/SKILL.md`

### 验证安装

在 Claude Code 中输入：

```
/xhs help
```

如果看到帮助信息，说明安装成功 ✅

---

## 📋 命令总览

### 📝 内容生成类

| 命令 | 说明 | 示例 |
|:-----|:------|:-----|
| `plan` | 生成 N 天内容计划 | `/xhs plan 知识干货 7` |
| `post` | 生成单篇完整笔记 | `/xhs post 用AI做PPT` |
| `title` | 生成 10 个爆款标题 | `/xhs title 打工人效率` |
| `prompt` | 生成万能 AI Prompt | `/xhs prompt 周报` |
| `video` | 生成视频脚本 | `/xhs video AI做PPT` |
| `calendar` | 月度内容日历 | `/xhs calendar 6月` |
| `script` | 话术库（80+ 模板） | `/xhs script 开场` |

### 🔍 分析优化类

| 命令 | 说明 | 示例 |
|:-----|:------|:-----|
| `analyze` | 竞品账号分析 | `/xhs analyze @竞品名` |
| `trending` | 热点追踪 | `/xhs trending AI` |
| `seo` | 小红书 SEO 优化 | `/xhs seo AI工具` |
| `review` | 爆款内容复盘 | `/xhs review [笔记内容]` |
| `check` | 检查笔记质量 | `/xhs check [笔记内容]` |

### 🏥 账号诊断类

| 命令 | 说明 | 示例 |
|:-----|:------|:-----|
| `diagnose` | 账号全面诊断 | `/xhs diagnose [账号信息]` |
| `stage` | 当前阶段指引 | `/xhs stage 0-1000粉` |
| `persona` | 人设打造指南 | `/xhs persona AI工具` |

### 💬 运营互动类

| 命令 | 说明 | 示例 |
|:-----|:------|:-----|
| `reply` | 评论区高情商回复 | `/xhs reply [评论内容]` |
| `avoid` | 避坑指南 | `/xhs avoid 新手期` |
| `weekly` | 数据复盘 + 下周计划 | `/xhs weekly [本周数据]` |

### 💰 变现类

| 命令 | 说明 | 示例 |
|:-----|:------|:-----|
| `monetize` | 变现路径规划 | `/xhs monetize 5000粉 知识干货` |

---

## 💡 使用示例

### 从零起号

```
# 1. 生成 7 天内容计划
/xhs plan 知识干货 7

# 2. 优化某一天的内容
/xhs post 用AI做PPT

# 3. 检查质量
/xhs check [粘贴内容]

# 4. 一周后复盘
/xhs weekly [粘贴数据]
```

### 竞品分析

```
# 1. 分析竞品
/xhs analyze @AI工具小王

# 2. 追踪热点
/xhs trending AI

# 3. 找差异化定位
/xhs persona AI工具
```

### 视频制作

```
# 1. 生成视频脚本
/xhs video AI做PPT --duration 60

# 2. 获取话术
/xhs script 开场

# 3. SEO 优化
/xhs seo AI做PPT
```

### 一鱼多吃

```
# 一个主题，多个平台版本
/xhs post AI做PPT --all

# 同时生成：
# ├── 小红书图文版
# ├── 视频脚本版
# ├── 朋友圈文案版
# └── 公众号文章框架版
```

---

## 📖 命令参数

### 通用参数

| 参数 | 说明 | 命令 |
|:-----|:------|:-----|
| `--series` | 系列化名称 | `plan` |
| `--all` | 一鱼多吃模式 | `post` |
| `--style` | 风格（口语/专业/搞笑/文艺） | `post` |
| `--type` | 标题类型 | `title` |
| `--duration` | 视频时长（秒） | `video` |
| `--vs` | 竞品对比 | `check` |

### 赛道选项

```
知识干货 | 生活方式 | 创意内容 | 变现导向 | 自定义
```

### 标题类型

```
数字 | 痛点 | 悬念 | 对比 | 身份 | 反问 | 挑战
```

### 话术场景

```
开场 | 关注 | 收藏 | 评论 | 私信 | 链接 | 转化 | 回复
```

---

## 🧠 内置知识库

### 爆款公式

```
标题 = 数字 + 痛点 + 解决方案
内容 = 痛点引入 + 解决方案 + 具体步骤 + 互动引导
涨粉 = 日更 + 蹭热点 + 互动引流 + 系列化内容
视频 = Hook(3秒) + 痛点(7秒) + 内容(40秒) + CTA(10秒)
```

### SEO 原则

```
标题必须包含核心关键词
正文前 100 字包含核心关键词
标签覆盖核心词 + 长尾词
关键词密度：2-3%
不要堆砌关键词
```

### 标签策略

```
2 个大流量标签（#AI #效率提升）
3 个中流量标签（#打工人 #办公技巧）
2 个精准标签（#Gamma #PPT教程）
```

### 发布时间

| 时段 | 工作日 | 周末 |
|:-----|:-------|:-----|
| 早 | 7:00-9:00 | 10:00-11:00 |
| 中 | 12:00-14:00 | — |
| 晚 | 18:00-22:00 | 19:00-20:00 |

> 💡 **最佳发布时间：** 周三/周五晚上

### 变现阶梯

| Level | 方式 | 粉丝要求 | 预期月收入 |
|:------|:------|:---------|:-----------|
| 1 | 接广告 | 1,000+ | ¥500-2,000 |
| 2 | 卖资料 | 0+ | ¥1,000-5,000 |
| 3 | 引流私域 | 3,000+ | ¥3,000-10,000 |
| 4 | 知识付费 | 5,000+ | ¥5,000-50,000 |
| 5 | 品牌合作 | 10,000+ | ¥10,000+ |
| 6 | 矩阵放大 | 50,000+ | ¥50,000+ |

---

## 📁 项目结构

```
xhs-skill/
├── README.md              # 项目说明（本文件）
├── SKILL.md               # Claude Code Skill 定义文件
├── LICENSE                 # MIT 开源协议
├── CONTRIBUTING.md         # 贡献指南
├── CHANGELOG.md            # 版本更新记录
├── docs/
│   └── manual.md           # 完整说明书
└── examples/
    └── 7day-plan.md        # 7 天起号计划示例
```

---

## 📚 文档

| 文档 | 说明 |
|:-----|:------|
| [SKILL.md](SKILL.md) | Skill 定义文件，Claude Code 读取的核心 |
| [说明书](docs/manual.md) | 完整使用手册，包含所有命令详解 |
| [7天起号计划](examples/7day-plan.md) | 知识干货赛道 7 天起号完整示例 |
| [更新日志](CHANGELOG.md) | 版本更新记录 |

---

## 🤝 贡献

欢迎贡献代码、提出建议或报告问题！

### 如何贡献

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建 Pull Request

### 贡献方向

- 🆕 新增子命令
- 📝 优化现有命令的输出
- 🧠 补充内置知识库
- 🐛 修复 Bug
- 📖 完善文档
- 🌐 多语言支持

详见 [CONTRIBUTING.md](CONTRIBUTING.md)

---

## ⚠️ 免责声明

- 本工具仅供学习和参考使用
- 生成的内容需要用户自行审核和修改
- 请遵守小红书平台规则和相关法律法规
- 使用本工具产生的任何后果由用户自行承担

---

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

---

## 🙏 致谢

- [Claude Code](https://claude.ai/code) — AI 编程助手
- [小红书](https://www.xiaohongshu.com) — 内容平台

---

<div align="center">

**如果这个项目对你有帮助，请给一个 ⭐ Star！**

[![Star History Chart](https://api.star-history.com/svg?repos=moc81966-maker/xhs-skill&type=Date)](https://star-history.com/#moc81966-maker/xhs-skill&Date)

</div>
