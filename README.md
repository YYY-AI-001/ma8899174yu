# 源力魔方 | AI 工作流研究所

<div align="center">

![Banner](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D9FF&background=111827&center=true&vCenter=true&random=false&width=620&lines=AI+Workflow+%2F+ComfyUI+%2F+AI+Video;%E6%8A%8AAI%E7%94%9F%E6%88%90%E5%8F%98%E6%88%90%E5%8F%AF%E5%A4%8D%E7%94%A8%E7%9A%84%E5%88%9B%E4%BD%9C%E6%B5%81%E7%A8%8B)

<p align="center">
  <a href="https://space.bilibili.com/3546745917148074" target="_blank">
    <img src="https://img.shields.io/badge/B%E7%AB%99-%E6%BA%90%E5%8A%9B%E9%AD%94%E6%96%B9%E7%A0%94%E7%A9%B6%E6%89%80-00A1D6?style=flat-square&logo=bilibili" alt="B站"/>
  </a>
  <a href="https://www.runninghub.cn/user-center/1925572233727475713/webapp?inviteCode=rh-v1065" target="_blank">
    <img src="https://img.shields.io/badge/RunningHub-%E5%B7%A5%E4%BD%9C%E6%B5%81%E5%AD%A6%E4%B9%A0-6C5CE7?style=flat-square" alt="RunningHub"/>
  </a>
  <img src="https://img.shields.io/badge/Focus-ComfyUI%20%7C%20AI%20Video%20%7C%20Prompts-FF6B6B?style=flat-square" alt="Focus"/>
  <img src="https://img.shields.io/badge/Codex-Skills-111827?style=flat-square" alt="Codex Skills"/>
</p>

</div>

## 我在做什么

**源力魔方** 是一个围绕 **AI 工作流教程** 搭建的内容与工具资产项目。

我关注的不是“某个模型又出了什么效果”，而是更底层的问题：

> 怎么把 AI 生图、AI 视频、ComfyUI、提示词和云端平台，整理成普通人能理解、能复用、能持续迭代的工作流。

当前主线是：

- **B站**：3 分钟 AI 工作流扫盲 + ComfyUI 实操教程
- **公众号**：免费图文教程、模型观察、工具资讯沉淀
- **GitHub**：提示词资产、Codex Skills、工作流说明文档
- **RunningHub**：云端工作流学习与案例承接
- **知识星球**：系统教程、专题拆解、资料库和答疑

## 适合谁看

| 你是谁 | 这里能帮你什么 |
|------|------|
| AI 生图新手 | 先建立模型、提示词、节点、工作流的基础地图 |
| ComfyUI 初学者 | 从“跑通案例”开始，而不是一上来硬啃节点 |
| AI 视频创作者 | 把故事拆成分镜、首尾帧、角色一致性和视频 prompt |
| 内容创作者 | 把 prompt、选题、脚本和图文沉淀成可复用资产 |
| 想做 AI 副业的人 | 参考一套从内容流量到资料包、社群和工具承接的路径 |

## 内容地图

| 模块 | 代表内容 | 状态 |
|------|------|------|
| AI 工作流扫盲 | 模型、提示词、LoRA、ControlNet、云端平台怎么理解 | 更新中 |
| ComfyUI 入门 | 工作流导入、节点理解、报错排查、案例拆解 | 更新中 |
| 国产/开源模型观察 | Qwen-Image、Z-Image、GLM-Image、ERNIE-Image 等 | 更新中 |
| AI 视频分镜 | Seedance 2.0、首尾帧、镜头运动、角色一致性 | 建设中 |
| 提示词资产管理 | 把一次性 prompt 变成模板、标签、版本和资产卡片 | 已整理 |
| Codex Skills | 面向创作工作流的可复用 AI 助手技能 | 已整理 |

## 仓库结构

```text
.
├── README.md
├── docs/
│   ├── ip-positioning.md
│   ├── content-system.md
│   └── conversion-map.md
└── skills/
    ├── README.md
    ├── prompt-asset-director/
    │   ├── SKILL.md
    │   └── agents/openai.yaml
    └── seedance-storyboard-director/
        ├── SKILL.md
        └── agents/openai.yaml
```

## Codex Skills

| Skill | 用途 | 入口 |
|------|------|------|
| 提示词资产导演 | 整理、优化、分类并版本化可复用提示词 | [prompt-asset-director](./skills/prompt-asset-director/SKILL.md) |
| Seedance 分镜导演 | 逐镜锁定分镜、角色一致性与 Seedance 2.0 prompt | [seedance-storyboard-director](./skills/seedance-storyboard-director/SKILL.md) |

调用示例：

```text
用 $prompt-asset-director 把这个提示词整理成可复用资产。
```

```text
用 $seedance-storyboard-director 把这个故事拆成 Seedance 2.0 分镜。
```

## 项目文档

- [IP 定位](./docs/ip-positioning.md)：源力魔方的人设、内容边界和表达风格
- [内容系统](./docs/content-system.md)：B站、公众号、GitHub、RunningHub、知识星球如何分工
- [承接链路](./docs/conversion-map.md)：从公开视频到资料包、技能资产和深度教程的转化路径
- [Skills 索引](./skills/README.md)：当前已整理的 Codex Skills

## 当前阶段目标

短期北极星目标：**B站 3000 粉**。

阶段重点：

- 每周 2 条视频，优先做系列化内容
- 公众号承接免费视频图文教程和工具观察
- GitHub 沉淀提示词资产、skills 和公开资料
- RunningHub 前期轻植入，用于云端工作流演示和学习承接
- 知识星球承接系统教程、专题讲解、资料库和答疑

## 技术栈

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![ComfyUI](https://img.shields.io/badge/ComfyUI-00D9FF?style=flat-square)
![Stable Diffusion](https://img.shields.io/badge/Stable%20Diffusion-FF6B6B?style=flat-square)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown)

</p>

## GitHub 数据

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=ma8899174yu&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ma8899174yu&layout=compact&theme=radical)

</div>

---

<div align="center">

**让 AI 创作从“抽卡”变成可复用的工作流。**

</div>
