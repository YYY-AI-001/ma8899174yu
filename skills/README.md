# Codex Skills

这里收纳「源力魔方」AI 工作流体系中可复用的 Codex Skills。

这些 skills 的目标不是炫技，而是把重复出现的创作流程沉淀下来：

- 提示词怎么整理成资产
- 视频故事怎么拆成分镜
- 角色一致性怎么锁定
- AI 生图/视频 prompt 怎么变成可复用模板

## Skill 列表

| Skill | 中文名 | 解决什么问题 |
|------|------|------|
| [prompt-asset-director](./prompt-asset-director/SKILL.md) | 提示词资产导演 | 将零散提示词整理、优化、分类并沉淀为可复用资产 |
| [seedance-storyboard-director](./seedance-storyboard-director/SKILL.md) | Seedance 分镜导演 | 为 Seedance 2.0 / AI 视频创作设计分镜、角色一致性和提示词 |

## 使用方式

将对应 skill 目录复制到本地 Codex skills 目录：

```text
~/.codex/skills/prompt-asset-director/
~/.codex/skills/seedance-storyboard-director/
```

然后在 Codex 中用 `$skill-name` 调用：

```text
用 $prompt-asset-director 把这个提示词整理成可复用资产。
```

```text
用 $seedance-storyboard-director 把这个短片想法拆成 6 个 Seedance 分镜。
```

## 迭代方向

后续计划补充：

- ComfyUI 工作流排错 skill
- 公众号图文排版 skill
- B站视频脚本拆解 skill
- AI 模型观察与资料整理 skill

