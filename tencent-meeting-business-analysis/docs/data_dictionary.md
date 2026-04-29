# Data Dictionary

## 通用字段说明

| 字段 | 含义 |
|---|---|
| metric_category / signal_category | 指标类别，用于区分用户规模、商业化、行业市场等 |
| metric_name / indicator | 指标名称 |
| year | 年份；Zoom等竞品如为财年需结合period和fiscal_year_flag查看 |
| period | 具体时间范围，如FY2024、2024Q4、2023-09 |
| value | 指标数值；如为“未公开披露”则不进入可视化计算 |
| unit | 单位 |
| source_url | 公开来源链接，便于审计 |
| credibility | 可信度，高/中高/中/低 |
| notes | 口径限制、使用限制、复核提示 |

## 可信度评级

| 等级 | 标准 |
|---|---|
| 高 | 官方财报、公司官网、官方发布会、权威机构正式报告 |
| 中高 | 权威媒体转述官方信息、机构报告摘要 |
| 中 | 第三方估算、二手统计平台、需要进一步复核的数据 |
| 低 | 无明确出处或无法追溯来源的数据；本数据包未作为核心数据使用 |

## 关键布尔字段

| 字段 | 含义 |
|---|---|
| can_plot_trend | 是否适合画趋势图 |
| officially_undisclosed | 是否官方未披露 |
| can_represent_tencent_meeting | 是否可以代表腾讯会议业务 |
| is_estimated | 是否为推算值或预测值 |
| fiscal_year_flag | 是否为财年口径 |
