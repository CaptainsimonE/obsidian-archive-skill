# Obsidian Archive（对话与内容归档 Skill）

把用户提供的内容（对话、文本、笔记）**完整归类、格式化、规范化**，沉淀进 Obsidian 库（PARA 体系）的 WorkBuddy Skill。

## 用途

用户只负责提供内容，分类与排版由本 skill 完成：

- **知识问答** → 整理为知识笔记（30-Resources 主题子文件夹）
- **项目讨论** → 整理为项目笔记（10-Projects）
- **日常内容** → 追加到当日日记（20-Areas 年度记录）
- **无法归类** → 放入 Inbox（00-Inbox）

产出遵循库内既有规范：中文扁平标签、YAML frontmatter、双链关联、MOC 维护。

## 文件结构

```
obsidian-archive/
├── SKILL.md               # 主流程（触发条件 / 工作流 / 归类决策树 / 规范化铁律）
└── references/
    └── templates.md       # 笔记模板（知识笔记 / 对话总结 / 项目进展 / 日记追加）
```

## 部署

1. 将本仓库放入 WorkBuddy skills 目录：
   - 用户级：`~/.workbuddy/skills/obsidian-archive/`
2. 编辑 `SKILL.md` 的「配置（CONFIG）」段落，把 `<VAULT_ROOT>` 替换为你自己的 Obsidian 库绝对路径
3. 按需调整 `references/templates.md` 中的模板与标签习惯

## 许可

MIT
