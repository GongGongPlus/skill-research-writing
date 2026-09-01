---
name: research-writing
description: 科研写作与学术研究技能。覆盖论文各章节写作方法（摘要/引言/方法/实验/相关工作）、文献综述与PRISMA检索流程、引用管理与BibTeX格式、统计检验选择与效应量、实验设计（样本量/随机化/伪重复）、科研图表出版规范、不确定度与单位报告、科研诚信（证据分级、禁止编造引用）。触发词：科研、论文写作、SCI、期刊、摘要、引言、方法、实验部分、文献综述、引用、参考文献、BibTeX、统计检验、p值、效应量、样本量、功效分析、图表规范、不确定度、科研诚信、academic writing, scientific writing, literature review, citation, BibTeX, statistics, hypothesis testing, effect size, power analysis, figure guidelines, uncertainty, research integrity。用于：撰写/修改学术论文、做文献综述、选统计方法、设计实验、制作出版级图表、规范报告不确定度等场景。
metadata:
  agent_created: true
---

# Research Writing（科研写作与分析）

从文献检索到出版图表的学术写作技能。核心立场：**流畅的句子不是证据**——每个事实主张可溯源；结论按证据分级（已确认 / 工程推论 / 估算 / 待验证 / 数据不足）。

## 症状 → 加载哪个 reference

| 症状 / 任务 | 加载 |
|---|---|
| 写/改任何章节：摘要、引言、方法、实验、相关工作、表格 | `references/paper-writing.md` |
| 选统计检验；样本量；p 值怎么报；审稿人质疑统计 | `references/statistics.md` |
| 查文献、做综述；BibTeX 报错；引用格式 | `references/citation-literature.md` |
| 图表出版规范；不确定度怎么写；单位换算 | `references/figures-units.md` |
| 引用可信吗；哪些能写进论文；AI 生成内容边界 | `references/integrity.md` |

## 工作流（写论文默认顺序）

1. **证据注册表**：每个主张 → 已验证证据 ID（原文定位，不是搜索片段）。
2. **大纲倒推**：先答"解决什么问题、贡献是什么、为何成立"，再顺写。
3. **章节写作**：Introduction 四段链；Method 三要素；实验三问。
4. **统计**：按决策树选检验；APA 五要素报告。
5. **图表**：期刊尺寸/分辨率规范；不确定性报告规则。
6. **交叉审计**：摘要↔正文↔表↔图数字一致；单位/分母/n 一致。

## 铁律

**MUST**
- 禁止编造引用、DOI、PMID、数据值、样本量、伦理批准号——缺失必须显式标注 missing，不得用貌似合理的样板话补齐。
- 每条事实/数字主张映射到已验证证据 ID；搜索片段、生成摘要、他人参考文献只可用于发现，不可用于验证。
- 图表不得篡改/隐藏/选择性增强数据；柱状/面积图含零基线；不静默连接缺失观测。
- 颜色不能是唯一编码通道——叠加形状/线型/文字标签。
- 报告不确定度必须命名区间类型（SD/SE/CI）与重复单位；先舍入不确定度，值再舍入到同一小数位。
- 不确定度/单位：温度差用 delta 单位；对数单位先转线性再算术。

**NOT**
- 不得为让论文"看起来一致"而由结果反推重建方法。
- 不得通过换检验/挑子群/剔离群值直到 p<.05；计划检验不显著本身就是结果。
- 不得事后计算 observed power（循环论证），改做敏感性分析。
- 不得把关联写成因果、把不显著写成等效、把 post hoc 改标 prespecified。
- 不得将未发表稿件/同行评审材料/PHI 上传外部服务；AI 不得用于伪造科研数据图像。
- 不得声称"无先例工作"除非有检索验证。

## 参考索引

5 个 reference 按"第一步→判据→如何证明"组织。统计检验决策树在 `statistics.md`；期刊尺寸速查表（Nature/Elsevier）在 `figures-units.md`。

