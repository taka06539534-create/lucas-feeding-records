# Lucas Feeding Records

新生儿喂养护理记录归档项目。每日记录会整理为 Markdown 日报、结构化 JSON 和可视化图表，默认入口是各报告目录下的 `index.md`。

## 快速入口

- 宝宝基础信息：[baby-info.md](baby-info.md)
- 项目级 Codex 指令：[AGENTS.md](AGENTS.md)
- 报告目录：[reports/](reports/)

## 喂养记录索引

| 记录日期 | 日报入口 | 结构化数据 | 可视化视图 | 原始输入 |
|---|---|---|---|---|
| 2026-06-25 | [index.md](reports/2026-06-25-baby-feeding-report/index.md) | [structured-data.json](reports/2026-06-25-baby-feeding-report/structured-data.json) | [SVG](reports/2026-06-25-baby-feeding-report/baby-feeding-report.svg) / [HTML](reports/2026-06-25-baby-feeding-report/baby-feeding-report.html) | [input.json](2026-06-25-baby-feeding-report-input.json) |
| 2026-06-27 | [index.md](reports/2026-06-27-baby-feeding-report/index.md) | [structured-data.json](reports/2026-06-27-baby-feeding-report/structured-data.json) | [SVG](reports/2026-06-27-baby-feeding-report/baby-feeding-report.svg) / [HTML](reports/2026-06-27-baby-feeding-report/baby-feeding-report.html) | [input.json](2026-06-27-baby-feeding-report-input.json) |
| 2026-06-28 | [index.md](reports/2026-06-28-baby-feeding-report/index.md) | [structured-data.json](reports/2026-06-28-baby-feeding-report/structured-data.json) | [SVG](reports/2026-06-28-baby-feeding-report/baby-feeding-report.svg) / [HTML](reports/2026-06-28-baby-feeding-report/baby-feeding-report.html) | [input.json](2026-06-28-baby-feeding-report-input.json) |

## 维护说明

- 新增、重生成或删除任意喂养记录后，同步更新上方“喂养记录索引”。
- 分析记录前先读取 `baby-info.md`，并在报告中结合宝宝基础信息；无法可靠解析的信息应在报告中标注不确定性。
- 可视化图表中的长文本需要换行或压缩为短句，详细说明放入 Markdown 正文。
- PNG 依赖本机浏览器截图能力；如果 PNG 未生成，保留 SVG 和 HTML 作为可视化入口。
