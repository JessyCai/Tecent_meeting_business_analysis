# 腾讯会议业务经营分析数据包

## 项目背景

本项目基于公开信息，整理腾讯会议业务经营分析所需的核心指标数据。腾讯会议并非独立披露主体，其收入、付费用户数、ARPU、留存率等核心经营指标未公开披露，因此本数据包采用公开披露数据、腾讯ToB板块数据、行业市场数据和竞品对标数据进行结构化整理。

## 数据文件说明

| 路径 | 说明 |
|---|---|
| `data/processed/tencent_meeting_core_metrics.csv` | 腾讯会议用户、使用、生态相关指标 |
| `data/processed/tencent_meeting_commercial_signals.csv` | 腾讯会议商业化信号指标 |
| `data/processed/tencent_group_segment_metrics.csv` | 腾讯金融科技及企业服务等板块指标 |
| `data/processed/industry_market_metrics.csv` | 视频会议、云会议、在线办公、SaaS等行业指标 |
| `data/processed/competitor_metrics.csv` | 钉钉、飞书、Zoom、Teams等竞品指标 |
| `data/processed/data_gap_table.csv` | 公开渠道无法获得的核心指标缺口说明 |
| `data/final/final_indicator_dataset.xlsx` | 汇总Excel版本，多sheet |
| `data/final/final_indicator_dataset.md` | GitHub可预览版数据摘要 |
| `docs/data_dictionary.md` | 字段说明 |
| `docs/data_quality_notes.md` | 数据质量与口径说明 |

## 核心口径说明

1. 腾讯会议累计用户数不等于MAU或DAU。
2. 腾讯会议收入绝对值未公开披露。
3. 腾讯金融科技及企业服务收入不能代表腾讯会议收入。
4. 行业市场数据因机构口径不同，不混合绘制趋势线。
5. Zoom采用财年口径，钉钉和飞书多为关键节点披露。

## 建议使用方式

- 做趋势图：优先使用 `tencent_group_segment_metrics.csv`、`industry_market_metrics.csv` 中明确标注 `can_plot_trend=是` 的数据。
- 做腾讯会议发展时间线：使用 `tencent_meeting_core_metrics.csv`。
- 做商业化判断：使用 `tencent_meeting_commercial_signals.csv`，但不要估算腾讯会议确定收入。
- 做竞品对比：使用 `competitor_metrics.csv`。
- 解释数据缺失：使用 `data_gap_table.csv`。
