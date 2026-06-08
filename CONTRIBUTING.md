# 贡献指南

感谢你对 XHS Skill 项目的关注！我们欢迎任何形式的贡献。

---

## 如何贡献

### 报告 Bug

1. 在 [Issues](https://github.com/moc81966-maker/xhs-skill/issues) 中搜索是否已有相同问题
2. 如果没有，创建新的 Issue
3. 使用 Bug 报告模板，包含：
   - 问题描述
   - 复现步骤
   - 期望行为
   - 实际行为
   - 环境信息

### 提出新功能

1. 在 [Issues](https://github.com/moc81966-maker/xhs-skill/issues) 中创建 Feature Request
2. 说明功能用途和使用场景
3. 如果可能，提供示例命令和输出

### 提交代码

```bash
# 1. Fork 仓库
# 2. 克隆到本地
git clone https://github.com/moc81966-maker/xhs-skill.git

# 3. 创建功能分支
git checkout -b feature/amazing-feature

# 4. 进行修改

# 5. 提交更改
git commit -m 'feat: add amazing feature'

# 6. 推送到远程
git push origin feature/amazing-feature

# 7. 创建 Pull Request
```

---

## 提交规范

使用 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

### Type 类型

| 类型 | 说明 |
|:-----|:------|
| `feat` | 新功能 |
| `fix` | Bug 修复 |
| `docs` | 文档更新 |
| `style` | 代码格式（不影响功能） |
| `refactor` | 重构 |
| `perf` | 性能优化 |
| `test` | 测试 |
| `chore` | 构建/工具变更 |

### 示例

```
feat(video): 新增 180 秒视频脚本支持
fix(plan): 修复系列化内容日期计算错误
docs(readme): 更新安装说明
```

---

## 开发指南

### 项目结构

```
xhs-skill/
├── SKILL.md           # Skill 核心定义
├── README.md          # 项目说明
├── LICENSE            # 开源协议
├── CONTRIBUTING.md    # 贡献指南
├── CHANGELOG.md       # 更新日志
├── docs/
│   └── manual.md      # 完整说明书
└── examples/
    └── 7day-plan.md   # 示例
```

### 修改 SKILL.md

SKILL.md 是 Claude Code 读取的核心文件，修改时注意：

1. **保持 YAML frontmatter 完整**
   ```yaml
   ---
   name: xhs
   description: "..."
   ---
   ```

2. **命令格式统一**
   ```
   ### 命令名 `<参数> [--可选参数]`
   ```

3. **示例要完整**
   ```
   /xhs 命令 参数
   ```

4. **输出格式清晰**
   - 使用 Markdown 表格
   - 使用代码块
   - 使用 emoji 增加可读性

### 新增子命令

添加新命令时，需要更新以下文件：

1. `SKILL.md` — 添加命令说明
2. `README.md` — 在命令总览中添加
3. `docs/manual.md` — 添加详细说明
4. `CHANGELOG.md` — 记录变更

### 命令设计原则

1. **简单易用** — 参数尽量少，有合理默认值
2. **输出清晰** — 使用 emoji、表格、代码块
3. **可组合** — 命令之间可以串联使用
4. **有示例** — 每个命令都要有使用示例

---

## 文档规范

### 语言风格

- 简洁明了
- 使用中文
- 适当使用 emoji
- 代码块标注语言类型

### 格式规范

- 标题使用 ATX 风格（`#`）
- 代码块使用三个反引号
- 表格对齐使用 `:---`
- 列表使用 `-` 或数字

---

## 行为准则

### 我们的承诺

- 尊重每一位贡献者
- 接受建设性批评
- 关注对社区最有利的事情
- 对他人表示同理心

### 不可接受的行为

- 使用性暗示的语言或图像
- 恶意评论或人身攻击
- 公开或私下骚扰
- 未经许可发布他人私人信息

---

## 问题？

如有任何问题，欢迎在 [Issues](https://github.com/moc81966-maker/xhs-skill/issues) 中提问！

---

**感谢你的贡献！ 🙏**
