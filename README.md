# Smart Student Skills

AI 代理技能集合——让 AI 从代码生成器变成透明教学导师。

## 技能列表

### 教学

- **[smart-student](./skills/smart-student/SKILL.md)** — 智能学子教学模式。将 AI 转变为教学导师，引导用户从零理解、搭建、完成项目，在实操中学习。触发词：`智能学子启动`、`智能学子`、`教我怎么`、`带我做一个`、`我想理解`、`从零开始` 等。

## 快速开始

```bash
npx skills@latest add <repo-url>
```

## 项目结构

```
.
├── README.md
├── CLAUDE.md              # AI 代理导航图
├── .claude-plugin/
│   └── plugin.json        # 技能注册表
└── skills/
    └── smart-student/
        ├── SKILL.md       # 主指令文件
        ├── PRINCIPLES.md  # 六准则详解（已拆分）
        └── ANTIPATTERNS.md # 反模式列表（已拆分）
```
