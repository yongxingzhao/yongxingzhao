# CLAUDE.md

> 本仓库的 AI 协作完整约定见 [AGENTS.md](./AGENTS.md)，以下为 Claude Code 专用的补充指引。

## 项目概述

GitHub Profile 仓库（`yongxingzhao/yongxingzhao`），`README.md` 直接渲染为 GitHub 个人主页。仓库刻意精简，无构建流程、无依赖。

## 核心规则

- 严格遵守 [AGENTS.md](./AGENTS.md) 中的所有编辑、提交、敏感信息约定
- 不新增未经明确要求的文件或目录
- `README.md` 内容增删须作者授权，只做格式与排版调整
- 提交信息使用 Conventional Commits（`docs:` / `chore:` / `fix:` 等）

## Claude Code 行为约束

- 修改 `README.md` 前先读取当前内容，理解上下文再动手
- 不自动 commit / push，除非明确要求
- 破坏性操作（删除、覆盖、force push）前必须确认
- 遇到非自己产生的改动，先理解再配合，不擅自回滚
