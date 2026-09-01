# 文献检索与引用管理

**第一步该做什么**：按研究主题选数据库组合（≥3 个），记录每条检索式与检索日期——否则综述不可复现。

## 数据库选择表

| 需求 | 库 |
|---|---|
| 生物医学 | PubMed / PMC |
| 预印本 | arXiv / bioRxiv |
| 跨学科 | OpenAlex / Crossref |
| AI 引用图 | Semantic Scholar |
| OA 全文 | CORE / Unpaywall |

## 综述流程（PRISMA 式 7 阶段）

1. 定义 PICO/研究问题 → 2. 写检索式（布尔 + 字段限定）→ 3. 多库检索并记录 → 4. 去重 → 5. 按纳入/排除标准筛选（双人或双轮）→ 6. 数据提取 → 7. 综合写作。PRISMA 流程图报告各阶段数量。

引文分级经验值：0–3 年 20+ 引用 = Noteworthy、100+ = Highly Influential；3–7 年 500+ = Landmark；7 年 1000+ = Foundational。

## 引用格式速查

- APA：按首作者字母排序。
- Nature / Vancouver / IEEE：按出现顺序编号。
- 正文标注与文末列表格式逐条核对期刊 author guidelines。

## BibTeX 规则（高频报错源）

- 作者用 `and` 分隔（禁分号/逗号/&）。
- 专有名词/缩写用花括号保护：`{AlphaFold}`、`{MRI}`。
- 页码用 `--`；doi 字段裸 DOI（不带 `https://doi.org/` 前缀、结尾无句点）。
- 10+ 作者用 `and others`。
- @article 缺 volume/pages/doi 即不合格，先补全再格式化。

## 引用可信度分级（integrity 前置规则）

流畅句子不是证据；搜索片段/摘要/他人参考文献列表只算**发现线索**，必须打开原文定位到具体章节才算**验证**。每条引用记：来源文件、定位（页/节）、验证日期。

## 如何证明综述可信

① 检索式与日期留档，第三方可复现同样结果；② 纳入/排除标准先于筛选确定（防事后挑选）；③ 每条引用验证到原文层级（不是二级引用）。审稿人抽查 3 条引用能即时给出原文定位 = 合格。

## 引用可验证性铁律（全网对标补强，来源 academic-research-skills）

- 每条引用 MUST 能通过 DOI 或标题解析到可核验来源（Semantic Scholar / OpenAlex / Crossref / arXiv 四源）；解析失败标记 `unresolvable`，禁止直接引用。
- DOI 模糊度 < 0.70 视为引用错误（DOI_MISMATCH），MUST 修正后再引用。
- 检测疑似 AI 生成的扭曲学术短语（tortured phrases），发现即重写。
