# 科研写作与分析 / Research Writing and Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Open Source](https://img.shields.io/badge/status-open--source-brightgreen.svg)](#开源状态--open-source-status)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-black.svg)](SKILL.md)

> 连接文献检索、实验设计、统计分析、论文写作、引用管理和出版级图表的科研 Skill。
>
> A research skill connecting literature search, experimental design, statistics, paper writing, citation management, and publication-grade figures.

## 中文介绍

### 能力范围

- 把研究问题改写成可证伪假设
- 组织可追溯的文献检索与引用链
- 选择统计检验并报告效应量与不确定度
- 按章节职责撰写摘要、引言、方法、结果与讨论
- 制作符合单位、标注和输出格式要求的科研图表

### 适用场景

论文规划、文献综述、实验设计、统计复核、稿件修改和科研图表制作。

### 设计方式

`SKILL.md` 是唯一入口，先完成场景分诊，再按需读取 `references/` 中的专题资料。这样既保留关键约束，又避免把所有领域知识一次性装入上下文。脚本仅用于可重复、可验证的机械操作。

### 安装

```powershell
git clone https://github.com/GongGongPlus/skill-research-writing.git "$env:USERPROFILE\.codex\skills\research-writing"
```

安装后重新打开 Codex 会话，让 Skill 目录重新被发现。也可以直接在任务中点名 `$research-writing`。

### 使用示例

```text
请使用 $research-writing 处理这个任务，并把已验证事实、工程推论和待验证项分开报告。
```

### 证据与边界

不编造文献、DOI、实验数据或显著性；无法核验的陈述必须降级标注，因果结论需要匹配研究设计。

本仓库提供工作流与判断框架，不替代官方规则、专业认证、生产环境审批或真实设备验证。执行涉及资金、硬件熔丝、生产部署、外部提交等高风险操作前，必须取得明确授权。

## English

### Scope

- Turn research questions into falsifiable hypotheses
- Maintain traceable literature searches and citation chains
- Choose statistical tests and report effect sizes and uncertainty
- Write abstracts, introductions, methods, results, and discussions by section purpose
- Create scientific figures with correct units, labels, and output formats

### Best fit

Paper planning, literature reviews, experimental design, statistical review, manuscript revision, and scientific figures.

### Design

`SKILL.md` is the single entry point. It triages the request first and loads only the relevant files under `references/`. This preserves important constraints without loading the entire knowledge base into context. Scripts are reserved for repeatable, verifiable mechanical work.

### Installation

```bash
git clone https://github.com/GongGongPlus/skill-research-writing.git "$HOME/.codex/skills/research-writing"
```

Start a fresh Codex session after installation so the skill directory is rediscovered. You can also invoke it explicitly as `$research-writing`.

### Example prompt

```text
Use $research-writing for this task. Separate verified facts, engineering inferences, and items that still need validation.
```

### Evidence boundary

Never fabricate references, DOIs, experimental data, or significance; unverifiable claims must be labeled, and causal claims require an appropriate study design.

This repository provides workflows and decision support. It does not replace official rules, professional certification, production approval, or real-device validation. Explicit authorization is required before high-risk actions involving funds, hardware fuses, production deployment, or external submission.

## Repository structure / 仓库结构

```text
skill-research-writing/
|-- references/
|   |-- citation-literature.md
|   |-- figures-units.md
|   |-- integrity.md
|   |-- paper-writing.md
|   |-- statistics.md
|-- SKILL.md
```

Reference topics / 专题资料：

- `references/citation-literature.md`
- `references/figures-units.md`
- `references/integrity.md`
- `references/paper-writing.md`
- `references/statistics.md`

## Author / 作者

- Author and maintainer / 作者与维护者：**中北大学机器人协会续晋全**
- GitHub: [@GongGongPlus](https://github.com/GongGongPlus)
- Collection index / 总索引：[GongGongPlus/agent-skills-index](https://github.com/GongGongPlus/agent-skills-index)

The author statement identifies the maintainer and original integrator of this repository. Referenced third-party projects retain their own authorship and rights.

作者信息表示本仓库的维护者与原创整合者；被引用的第三方项目仍保留其原作者身份与相关权利。

## 开源状态 / Open-source status

- Visibility / 可见性：**Public / 公开**
- Status / 状态：**Open source / 开源**
- License / 许可证：[MIT](LICENSE)
- Warranty / 担保：按“原样”提供，不承诺适用于特定目的 / Provided as-is, without warranty
- Third-party boundary / 第三方边界：见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)

欢迎在遵守许可证与证据边界的前提下使用、修改和分发。Issues 与 Pull Requests 可用于报告可复现问题或提交改进。

Use, modification, and redistribution are welcome under the license and evidence boundaries. Issues and pull requests may be used for reproducible bug reports and improvements.
