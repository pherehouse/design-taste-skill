# 「设计师」Skill

这是一个可移植的 Agent Skill，用来给海报、品牌、产品、网页、UI、社媒、电商视觉推荐风格、配色、字体、版式和参考网站。知识库里有 100 个设计参考站、29 种风格、混搭方向，以及 AI 提示词模板。

网站核验状态以 **2026-11-14** 为准（当时 100 个站点中：已访问核验 97、无法访问 1、仅凭文章描述 2）。之后站点可能上线、下线或改版，推荐时请再确认。

## 安装

把 `skills/designer/` 整个文件夹复制到对应目录（保持文件夹名为 `designer`）：

- Claude Code：`~/.claude/skills/`
- Codex：`~/.codex/skills/`
- Gemini CLI：`~/.gemini/config/skills/`
- Grok Bot：把该文件夹作为 skill 上传

复制完成后，目录应为 `~/.claude/skills/designer/SKILL.md`（或其他工具的对应路径）。

## 使用示例

装好后可以直接问：

> 帮我给一个面向 25–35 岁的独立咖啡品牌做一套小红书海报方向：风格、配色、中英文字体，再给 4 个可以参考的网站。

## 目录

- `skills/designer/SKILL.md`：使用流程
- `skills/designer/references/`：知识库（索引、网站、风格、标签、混搭、提示词等）
- `skills/designer/references/data/`：与 markdown 同步的结构化数据

## 版权说明

本仓库未附带许可证。各网站的名称、简介与原文描述归其来源所有，本 skill 只做整理、核验与风格归纳，不构成对这些内容的授权转让。引用或再发布时请注明下方来源，并遵守各站点自身条款。

## 致谢

- 站点清单最初来自 Eian（@EianLu）《100 个提升审美的设计网站大赏》：https://x.com/EianLu/status/2121219503988113557
- 产出本知识库所使用的五轮分析提示词来自 OSen（@OxygenOvO2）：https://x.com/OxygenOvO2/status/2121559894717509850
