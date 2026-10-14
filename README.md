# Agent Skills（免费）

中文实战派 Agent Skills：把真实跑通的方法论打包成开箱即用的 Skill，装到你的 AI Agent 里直接用。

## Skills 列表

| Skill | 干什么 | 状态 |
|---|---|---|
| [x-ops-automation](x-ops-automation/SKILL.md) | X(Twitter)中文账号自动化运营：选题、写作、配图、发布、评论巡查全流程 | ✅ 可用 |

## 怎么安装

```bash
# 克隆仓库
git clone https://github.com/Tsla2000/agent-skills.git

# 把想要的 Skill 复制到你的 Agent skills 目录（以 Claude Code 为例）
cp -r agent-skills/x-ops-automation ~/.claude/skills/
```

其他 Agent 的安装路径：
- Codex: `~/.codex/skills/`
- Cursor: `~/.cursor/skills/`

装完直接跟你的 Agent 说"用 x-ops-automation 帮我运营 X 账号"，它就知道怎么做了。

## 这是什么规范

每个 Skill 是一个文件夹，里面有一份 `SKILL.md`（YAML frontmatter + Markdown 方法论），兼容 Anthropic Agent Skills 规范。Skill 不提供模型，模型用量由你自己的 Agent 服务商计费。

## 作者

PRO的茶里芒果 ｜ https://promangofund.com ｜ X @PRO_AI_99T
