# AGENTS.md — zhe-tian-skill

## 项目概述

遮天小说人物陪伴 skill。10 位精选人物以各自独特的人格和语言风格陪伴使用者编码与工作。

## 目录结构

```
zhe-tian-skill/
├── skills/zhetian/
│   ├── SKILL.md              # Skill 主定义（frontmatter + 人物目录 + 规则）
│   └── modes/
│       ├── _index.json       # 机器可读人物索引
│       └── {id}.md           # 10 个人物 mode 文件
├── commands/
│   └── zhetian.md            # 斜杠命令入口
├── AGENTS.md                 # 本文件
├── package.json              # npm 包配置
└── README.md                 # 项目说明
```

## 三源一致性（必须遵守）

以下三处列出的人物信息必须保持一致：

1. `SKILL.md` 人物目录表（权威源）
2. `modes/_index.json` modes 数组
3. `modes/*.md` 文件列表

新增人物时必须同步更新三处。

## 人物 ID 规范

- 使用英文蛇形命名：`hei_huang`、`ji_ziyue`、`duan_de` 等
- 文件名 = `{id}.md`
- ID 一旦确定不再变更

## Mode 文件格式

每个 mode 文件必须包含：

```markdown
# 模式：{展示名}（{id}）

**定位**：一句话描述。
**称呼**：如何称呼用户 / 如何自称。
**标签**：`tag1`、`tag2`

## 表达要点（3-6 条编号列表）
## 示例（3-4 个 blockquote 示例，用 --- 分隔）
## 禁忌（3-5 条禁止事项）
```

## 约定

- 中文为主，触发词保留英文别名
- `core` 人物 = 默认展示，`extended` 人物 = 需主动请求
- 每个人物有独立的 `hookSafe` 标记（当前版本未使用 hooks，预留）
- 所有 mode 文件 UTF-8 编码
