# CNB 技能索引

根据用户需求，匹配并调用当前项目中最合适的 CNB 子技能。

## 开始

执行 `cnb` 命令前，先用 `command -v cnb`（PowerShell 用 `Get-Command cnb`）检测；**仅当无输出时**按平台安装：

```bash
curl -fsSL https://cnb.cool/cnb/skills/cnb-skill/-/git/raw/main/install.sh | sh
```

```powershell
irm https://cnb.cool/cnb/skills/cnb-skill/-/git/raw/main/install.ps1 | iex
```

```bash
npm install @cnbcool/cnb-cli -g
```

## 平台与文档

- **cnb-api** — 调用 CNB 平台 API，操作仓库、Issue、PR、流水线、制品库等资源。
- **cnb-docs** — 查询 CNB 平台官方文档，覆盖代码托管、制品库、AI 助手、云原生构建和开发者工具。
- **cnb-repo-knowledge-base** — 检索指定 CNB 仓库的知识库，返回相关文本片段及来源。

## 代码与 PR

- **cnb-code-commit** — 编写代码、修复 Bug、重构优化、提交推送并创建或更新 PR。
- **cnb-code-review** — 评审 PR 代码变更，检查安全漏洞、Bug、代码质量和性能问题。
- **cnb-pr-diff** — 获取 PR diff 和文件变更，用于代码评审、变更分析等场景。
- **cnb-pr-summary** — 总结 PR 变更内容，概述主要改动点并生成变更说明。

## 流水线

- **cnb-pipeline** — 编写、修改、审查 `.cnb.yml`，诊断流水线失败原因并优化 CI 性能。
- **cnb-plugin-market** — 搜索 CNB 插件市场，找到匹配需求的插件，读取文档并生成正确的流水线插件配置。

## 协作与工具

- **cnb-upload-attachment** — 上传图片、文档、压缩包等附件到 Issue 或 PR 评论，并返回 Markdown 链接。
- **cnb-text-path-converter** — 将 Issue、PR 描述、评论、Review 中的相对路径转换为绝对路径。
- **cnb-npc-search** — 通过关键词语义搜索 CNB 平台上的公开 NPC 角色。
- **cnb-npc-delegate** — 当任务复杂、需要特定专长或可并行处理时，召唤其他 NPC 协同工作。
- **cnb-tapd-resource-fetcher** — 从 TAPD 链接解析并获取需求、缺陷、任务、迭代等资源数据。
