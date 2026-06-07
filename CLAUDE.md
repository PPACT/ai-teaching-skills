# Smart Student Skills — AI 代理导航

这是一个 Claude Code 技能（Skills）项目。技能是打包好的 AI 行为指令，通过 SKILL.md 定义，由 plugin.json 注册。

## 目录组织

```
skills/
└── smart-student/   # 教学类技能（当前唯一）
```

随着技能数量增加，将引入 bucket 分类目录（engineering/、productivity/、misc/ 等）。

## 技能约定

- 每个技能一个文件夹，必须包含 `SKILL.md`（主指令文件）
- SKILL.md 控制在 100 行以内，超出部分拆到子文件
- SKILL.md 的 frontmatter 中 `description` 字段决定 AI 何时加载该技能
- 子文件通过 Markdown 相对路径链接引用（如 `[PRINCIPLES.md](PRINCIPLES.md)`）
- 技能注册在 `.claude-plugin/plugin.json`

## 当前技能

- **smart-student**: 教学导师模式。触发词包括 `智能学子启动`、`智能学子`、`教我怎么`、`带我做一个`、`我想理解`、`我想学`、`怎么做`、`从零开始`、`从零搭建`。
