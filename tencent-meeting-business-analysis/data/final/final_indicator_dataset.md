# 腾讯会议业务经营分析——最终指标数据集

> 本数据集基于公开数据和前期交叉验证整理。仅保留可用于后续分析的核心指标、商业化信号、腾讯板块代理指标、行业市场指标、竞品对标指标和数据缺口说明。

## 文件结构

| 文件 | 说明 |
|---|---|
| `tencent_meeting_core_metrics.csv` | 腾讯会议用户、使用、生态相关指标 |
| `tencent_meeting_commercial_signals.csv` | 腾讯会议商业化信号指标 |
| `tencent_group_segment_metrics.csv` | 腾讯金融科技及企业服务等板块指标 |
| `industry_market_metrics.csv` | 视频会议、云会议、在线办公、SaaS等行业指标 |
| `competitor_metrics.csv` | 钉钉、飞书、Zoom、Teams等竞品指标 |
| `data_gap_table.csv` | 公开渠道无法获得的核心指标缺口说明 |


## tencent_meeting_core_metrics

| metric_category | metric_name | year | period | value | unit | data_type | metric_scope | metric_definition_or_scope_note | credibility | can_plot_trend | use_in_report | source_url | notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 用户规模 | 腾讯会议累计用户数 | 2020 | 2020-09 | 1 | 亿人以上 | 关键节点 | 腾讯会议 | 用户数/累计用户数，非MAU/DAU | 高 | 否 | 是 | https://finance.sina.com.cn/wm/2020-09-14/doc-iivhuipp4331042.shtml | 腾讯会议上线245天用户数突破1亿 |
| 用户规模 | 腾讯会议累计用户数 | 2021 | 2021-12 | 2 | 亿人以上 | 关键节点 | 腾讯会议 | 用户数/累计用户数，非MAU/DAU | 高 | 否 | 是 | https://www.36kr.com/p/1547105074718725 | 用户数超过2亿 |
| 用户规模 | 腾讯会议累计用户数 | 2022 | 2022-11 | 3 | 亿人以上 | 关键节点 | 腾讯会议 | 用户数/累计用户数，非MAU/DAU | 高 | 否 | 是 | https://news.qq.com/rain/a/20221117A069W400 | 腾讯2022年Q3财报相关公开报道：用户数超3亿 |
| 用户规模 | 腾讯会议累计用户数 | 2023 | 2023-09 | 4 | 亿人以上 | 关键节点 | 腾讯会议 | 用户数/累计用户数，非MAU/DAU | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | 2023腾讯全球数字生态大会披露用户突破4亿 |
| 用户活跃 | DAU | 2020 | 2020-02 | 1000 | 万人以上 | 单点数据 | 腾讯会议 | 日活跃用户数 | 高 | 否 | 是 | https://www.fromgeek.com/daily/1044-344428.html | 上线两个月内DAU超过1000万；后续未持续披露 |
| 使用活跃 | 年度会议场次 | 2020 | FY2020 | 3 | 亿场以上 | 年度单点 | 腾讯会议 | 会议场次 | 高 | 否 | 是 | https://www.chinanews.com/business/2020/12-25/9371092.shtml | 2020年披露会议场次超过3亿场 |
| 使用活跃 | 年度参会次数 | 2021 | FY2021 | 40 | 亿次以上 | 年度单点 | 腾讯会议 | 参会次数，不等于会议场次 | 高 | 否 | 是 | https://finance.sina.cn/2021-11-03/detail-iktzqtyu5151120.d.html | 过去一年用户参会次数超过40亿次 |
| 平台生态 | 累计在线协同次数 | 2023 | 2023-09 | 25 | 亿次以上 | 关键节点 | 腾讯会议 | 累计在线协同次数 | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | 自上线以来累计在线协同次数超过25亿次 |
| 平台生态 | API日均调用次数 | 2023 | 2023-09 | 1000 | 万次以上 | 单点数据 | 腾讯会议开放平台 | API日均调用次数 | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | API日均调用过千万 |
| AI使用 | AI功能月活跃用户数 | 2024 | FY2024 | 1500 | 万人 | 年度单点 | 腾讯会议AI功能 | AI功能MAU，不是整体MAU | 高 | 否 | 是 | https://www.163.com/dy/article/JR3TJ1UD053144S4.html | 腾讯财报电话会议相关报道：AI功能MAU 1500万，同比增一倍 |
| 企业生态 | 基于API打造解决方案的企业 | 2023 | 2023-09 | 3000 | 家以上 | 关键节点 | 腾讯会议开放平台 | API生态企业，不是全部企业客户 | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | 数千家企业基于腾讯会议API打造解决方案 |

## tencent_meeting_commercial_signals

| signal_category | indicator | year | period | value | unit | absolute_or_growth | metric_scope | scope_note | officially_undisclosed | can_use_for_revenue_estimation | use_in_report | source_url | notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 收入 | 腾讯会议收入绝对值 | 2020 | FY2020 | 未公开披露 | — | 缺失指标 | 腾讯会议 | — | 是 | 否 | 否 | 公开渠道未发现腾讯会议单独收入 | 腾讯会议收入嵌入腾讯金融科技及企业服务等相关板块，不能拆分 |
| 收入 | 腾讯会议收入绝对值 | 2021 | FY2021 | 未公开披露 | — | 缺失指标 | 腾讯会议 | — | 是 | 否 | 否 | 公开渠道未发现腾讯会议单独收入 | 腾讯会议收入嵌入腾讯金融科技及企业服务等相关板块，不能拆分 |
| 收入 | 腾讯会议收入绝对值 | 2022 | FY2022 | 未公开披露 | — | 缺失指标 | 腾讯会议 | — | 是 | 否 | 否 | 公开渠道未发现腾讯会议单独收入 | 腾讯会议收入嵌入腾讯金融科技及企业服务等相关板块，不能拆分 |
| 收入 | 腾讯会议收入绝对值 | 2023 | FY2023 | 未公开披露 | — | 缺失指标 | 腾讯会议 | — | 是 | 否 | 否 | 公开渠道未发现腾讯会议单独收入 | 腾讯会议收入嵌入腾讯金融科技及企业服务等相关板块，不能拆分 |
| 收入增速 | 腾讯会议收入同比增速 | 2024 | 2024Q1 | 100 | %以上 | 增长率 | 腾讯会议 | 媒体转述口径 | 中 | 否 | 是 | https://www.21jingji.com/article/20240515/herald/3c4633844db3cd11d2e922db98115203.html | 2024Q1收入同比翻倍；非全年收入 |
| 收入增速 | 腾讯会议收入同比增速 | 2024 | 2024Q4 | 40 | %以上 | 增长率 | 腾讯会议 | 媒体/财报材料转述口径 | 高 | 否 | 是 | https://www.news.cn/tech/20250319/c9f58d07c3dc463e9a189533fd1337d5/c.html | 2024Q4收入同比增长超40%；未披露绝对收入 |
| 付费转化 | 付费用户数同比增速 | 2023 | 2023-09 | 5 | 倍 | 增长率 | 腾讯会议 | 仅披露增速，未披露绝对值 | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | 2023年9月披露付费用户数同比提升5倍 |
| 渠道商业化 | 代理收入同比增速 | 2023 | 2023H1 | 200 | % | 增长率 | 腾讯会议代理渠道 | 代理收入，不是总收入 | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | 2023H1代理收入同比增长200% |
| 生态 | 生态伙伴数 | 2022 | FY2022 | 100 | 家以上 | 绝对值 | 腾讯会议生态 | 生态伙伴，不是客户数 | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | 生态伙伴超过100家 |
| 生态 | 生态伙伴数 | 2023 | 2023-09 | 300 | 家以上 | 绝对值 | 腾讯会议生态 | 生态伙伴，不是客户数 | 高 | 否 | 是 | https://www.infoq.cn/article/dVusdTArjZDRQ1dwL8wo | 生态伙伴超过300家 |

## tencent_group_segment_metrics

| segment | metric_name | year | period | value | unit | yoy_growth_value | yoy_growth_unit | scope_note | can_represent_tencent_meeting | credibility | source_url | notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 金融科技及企业服务 | 板块收入 | 2020 | FY2020 | 1281 | 亿元 | 26 | % | 腾讯财报板块，含支付、理财、云服务、企业SaaS等 | 否 | 高 | https://static.www.tencent.com/uploads/2021/04/08/960eae1f18dd716fd3a7d704e123d7a5.pdf | 不能等同腾讯会议收入 |
| 金融科技及企业服务 | 板块收入 | 2021 | FY2021 | 1722 | 亿元 | 34 | % | 腾讯财报板块，含支付、理财、云服务、企业SaaS等 | 否 | 高 | https://www.tencent.com/zh-cn/investors/financial-news.html | 不能等同腾讯会议收入 |
| 金融科技及企业服务 | 板块收入 | 2022 | FY2022 | 1771 | 亿元 | 3 | % | 腾讯财报板块，含支付、理财、云服务、企业SaaS等 | 否 | 高 | https://www.sohu.com/a/657746013_481750 | 不能等同腾讯会议收入 |
| 金融科技及企业服务 | 板块收入 | 2023 | FY2023 | 2038 | 亿元 | 15 | % | 腾讯财报板块，含支付、理财、云服务、企业SaaS等 | 否 | 中高 | https://www.tencent.com/zh-cn/investors/financial-news.html | 需以腾讯2023年报原文复核；不能等同腾讯会议收入 |
| 金融科技及企业服务 | 板块收入 | 2024 | FY2024 | 2120 | 亿元 | 4 | % | 腾讯财报板块，含支付、理财、云服务、企业SaaS等 | 否 | 高 | https://news.qq.com/rain/a/20250321A039YQ00 | 不能等同腾讯会议收入 |
| 金融科技及企业服务 | 板块收入 | 2025 | FY2025 | 2294 | 亿元 | 8 | % | 腾讯财报板块，含支付、理财、云服务、企业SaaS等 | 否 | 高 | https://static.www.tencent.com/uploads/2026/03/18/559e5d480a4411165e6c7367d61fefbd.pdf | 不能等同腾讯会议收入 |
| 腾讯云 | 云收入估算 | 2020 | FY2020 | 256 | 亿元 |  |  | Canalys/第三方推算，非腾讯官方披露 | 否 | 中 | https://zhuanlan.zhihu.com/p/1888661892089741472 | 降级为辅助参考，不进入核心结论 |
| 腾讯云 | 云收入估算 | 2021 | FY2021 | 423 | 亿元 |  |  | Canalys/第三方推算，非腾讯官方披露；腾讯2021年后不再单独披露云收入 | 否 | 中 | https://zhuanlan.zhihu.com/p/1888661892089741472 | 降级为辅助参考，不进入核心结论 |

## industry_market_metrics

| market | metric_name | year | period | value | unit | source_institution | is_estimated | can_plot_trend | scope_note | credibility | source_url | notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 中国视频会议市场 | 总体规模 | 2020 | FY2020 | 9.5 | 亿美元 | IDC | 否 | 是 | 含硬件+云会议 | 高 | https://m.jiemian.com/article/6213228.html | IDC中国视频会议市场口径 |
| 中国视频会议市场 | 总体规模 | 2021 | FY2021 | 9.8 | 亿美元 | IDC | 是 | 谨慎 | 根据2022年同比下降2.8%反推 | 中 | https://www.199it.com/archives/1621197.html | 推算值，不建议作为强结论 |
| 中国视频会议市场 | 总体规模 | 2022 | FY2022 | 9.5 | 亿美元 | IDC | 否 | 是 | 含硬件+云会议 | 高 | https://www.199it.com/archives/1621197.html | IDC中国视频会议市场口径 |
| 中国视频会议市场 | 总体规模 | 2023 | FY2023 | 9.2 | 亿美元 | IDC | 否 | 是 | 含硬件+云会议 | 高 | https://www.c114.com.cn/market/39/a1267182.html | IDC中国视频会议市场口径 |
| 中国视频会议市场 | 总体规模 | 2024 | FY2024 | 9.8 | 亿美元 | IDC | 否 | 是 | 含硬件+云会议 | 高 | https://www.zhitongcaijing.com/content/detail/1310716.html | IDC中国视频会议市场口径 |
| 中国云会议市场 | 市场规模 | 2020 | FY2020 | 2.6 | 亿美元 | IDC | 否 | 否 | 云会议/软件SaaS细分，节点数据 | 高 | https://m.jiemian.com/article/6213228.html | 节点数据，不强行连线 |
| 中国云会议市场 | 市场规模 | 2024 | FY2024 | 3.0 | 亿美元 | IDC | 否 | 否 | 云会议/软件SaaS细分，节点数据 | 高 | https://www.zhitongcaijing.com/content/detail/1310716.html | 节点数据，不强行连线 |
| 中国硬件视频会议市场 | 市场规模 | 2020 | FY2020 | 6.9 | 亿美元 | IDC | 否 | 否 | 硬件视频会议细分，节点数据 | 高 | https://m.jiemian.com/article/6213228.html | 节点数据 |
| 中国硬件视频会议市场 | 市场规模 | 2024 | FY2024 | 6.7 | 亿美元 | IDC | 否 | 否 | 硬件视频会议细分，节点数据 | 高 | https://www.zhitongcaijing.com/content/detail/1310716.html | 节点数据 |
| 中国在线办公用户 | 用户规模 | 2020 | 2020-12 | 3.46 | 亿人 | CNNIC/中商整理 | 否 | 是 | 线上办公用户规模 | 高 | https://www.askci.com/news/chanye/20250315/142501274201990022151678.shtml | 建议回溯CNNIC原文确认 |
| 中国在线办公用户 | 用户规模 | 2021 | 2021-12 | 4.69 | 亿人 | CNNIC/中商整理 | 否 | 是 | 线上办公用户规模 | 高 | https://www.askci.com/news/chanye/20250315/142501274201990022151678.shtml | 建议回溯CNNIC原文确认 |
| 中国在线办公用户 | 用户规模 | 2022 | 2022-12 | 4.73 | 亿人 | CNNIC/中商整理 | 否 | 是 | 线上办公用户规模 | 中高 | https://www.askci.com/news/chanye/20250315/142501274201990022151678.shtml | 与部分版本数据存在差异，建议复核 |
| 中国在线办公用户 | 用户规模 | 2023 | 2023-12 | 5.37 | 亿人 | CNNIC/中商整理 | 否 | 是 | 线上办公用户规模 | 高 | https://www.askci.com/news/chanye/20250315/142501274201990022151678.shtml | 年末用户规模 |
| 中国在线办公用户 | 用户规模 | 2024 | 2024-12 | 5.7 | 亿人 | CNNIC/中商整理 | 否 | 是 | 线上办公用户规模 | 高 | https://www.askci.com/news/chanye/20250315/142501274201990022151678.shtml | 年末用户规模 |
| 中国企业级SaaS市场 | 市场规模 | 2020 | FY2020 | 538 | 亿元 | 艾瑞咨询 | 否 | 谨慎 | 企业级SaaS市场 | 中 | https://zhuanlan.zhihu.com/p/645904954 | 外延市场，非腾讯会议直接市场 |

> 仅预览前15行，完整数据见 `data/processed/industry_market_metrics.csv`。

## competitor_metrics

| company | product | metric_name | year | period | value | unit | fiscal_year_flag | metric_scope | credibility | source_url | notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 阿里巴巴 | 钉钉 | 用户数 | 2021 | FY2021 | 5 | 亿人以上 | 否 | 累计用户 | 高 | https://m.36kr.com/p/1077988267421577 | 非MAU，关键节点数据 |
| 阿里巴巴 | 钉钉 | 用户数 | 2022 | FY2022 | 6 | 亿人以上 | 否 | 累计用户 | 高 | https://zhuanlan.zhihu.com/p/594915767 | 非MAU，关键节点数据 |
| 阿里巴巴 | 钉钉 | 用户数 | 2023 | FY2023 | 7 | 亿人以上 | 否 | 累计用户 | 高 | https://m.thepaper.cn/baijiahao_25947745 | 非MAU，关键节点数据 |
| 阿里巴巴 | 钉钉 | 企业组织数 | 2021 | 2021-01 | 1700 | 万个以上 | 否 | 组织数 | 高 | https://t.cj.sina.com.cn/articles/view/1850460740/6e4bca4402000r5r4 | 含企业、学校等组织 |
| 阿里巴巴 | 钉钉 | 企业组织数 | 2023 | FY2023 | 2500 | 万个以上 | 否 | 组织数 | 高 | https://m.thepaper.cn/baijiahao_25947745 | 不是付费企业数 |
| 阿里巴巴 | 钉钉 | 软件付费企业数 | 2023 | FY2023 | 12 | 万家 | 否 | 付费企业 | 高 | https://m.thepaper.cn/baijiahao_25947745 | 国内竞品商业化对标 |
| 阿里巴巴 | 钉钉 | 付费DAU | 2023 | FY2023 | 2800 | 万人 | 否 | 付费活跃用户 | 高 | https://m.thepaper.cn/baijiahao_25947745 | 国内竞品商业化对标 |
| 阿里巴巴 | 钉钉 | ARR | 2024 | FY2025H1 | 2 | 亿美元以上 | 是 | 年度经常性收入 | 高 | https://www.ithome.com/0/810/508.htm | 阿里2025上半财年，非自然年 |
| 阿里巴巴 | 钉钉 | AI功能使用企业数 | 2024 | 2024-01 | 70 | 万家 | 否 | 使用AI功能企业 | 高 | https://finance.sina.com.cn/roll/2024-01-09/doc-inaawzyc7670602.shtml | AI办公对标 |
| 字节跳动 | 飞书 | ARR | 2022 | FY2022 | 1 | 亿美元 | 否 | 年度经常性收入 | 高 | https://www.sohu.com/a/641746974_120440231 | 非收入确认口径 |
| 字节跳动 | 飞书 | ARR | 2023 | FY2023 | 2 | 亿美元以上 | 否 | 年度经常性收入 | 高 | https://www.ithome.com/0/793/391.htm | 非收入确认口径 |
| 字节跳动 | 飞书 | ARR | 2024 | FY2024E | 3 | 亿美元以上 | 否 | 年度经常性收入 | 中高 | https://www.ithome.com/0/793/391.htm | 预计值 |
| 字节跳动 | 飞书 | MAU | 2024 | 2024-09 | 600 | 万人以上 | 否 | 月活跃用户 | 高 | https://news.qq.com/rain/a/20240906A07RLW00 | 单点披露，不画趋势 |
| Zoom | Zoom | 年收入 | 2021 | FY2021 | 26.51 | 亿美元 | 是 | 财年收入 | 高 | https://news.zoom.com/zoom-video-communications-reports-fourth-quarter-and-fiscal-year-2021-financial-results/ | Zoom财年截至1月31日 |
| Zoom | Zoom | 年收入 | 2022 | FY2022 | 40.99 | 亿美元 | 是 | 财年收入 | 高 | https://news.zoom.com/zoom-video-communications-reports-fourth-quarter-and-fiscal-year-2022-financial-results/ | Zoom财年截至1月31日 |

> 仅预览前15行，完整数据见 `data/processed/competitor_metrics.csv`。

## data_gap_table

| missing_metric | missing_period | officially_undisclosed | can_substitute | substitute_indicator | why_it_matters | risk_note |
|---|---|---|---|---|---|---|
| 腾讯会议收入绝对值 | 2020-2025 | 是 | 部分 | 收入同比增速、价格体系、腾讯ToB板块收入 | 判断商业化规模 | 不能写确定收入金额；板块收入≠腾讯会议收入 |
| 腾讯会议付费用户数绝对值 | 2020-2025 | 是 | 部分 | 2023年付费用户同比提升5倍 | 判断付费转化 | 不能计算真实付费渗透率 |
| 腾讯会议付费企业数 | 2020-2025 | 是 | 否 | 无 | 判断企业商业化规模 | 客户案例不能替代客户数 |
| 腾讯会议ARPU | 2020-2025 | 是 | 部分 | 专业版/商业版/Rooms/Webinar价格体系 | 判断单客户价值 | 只能做情景测算，不能当真实ARPU |
| 腾讯会议付费渗透率 | 2020-2025 | 是 | 否 | 无 | 判断转化效率 | 缺少付费用户数和可靠总活跃用户数 |
| 腾讯会议企业版客户数 | 2020-2025 | 是 | 部分 | 生态伙伴数、API企业数 | 判断企业客户生态 | 生态伙伴≠企业客户 |
| 腾讯会议季度经营数据 | 2020-2025大部分缺失 | 是 | 否 | 无 | 季度趋势分析 | 不可用年度/关键节点数据平均拆分季度 |
| 腾讯会议整体MAU | 2020-2025大部分缺失 | 是 | 不建议 | 第三方MAU估算 | 判断活跃规模 | 口径冲突，不进入核心图表 |
| 腾讯会议留存率 | 2020-2025 | 是 | 否 | 无 | 判断客户粘性 | 公开资料无法还原 |
| 腾讯会议客户行业结构 | 2020-2025 | 是 | 部分 | 典型客户案例、行业解决方案页面 | 判断行业渗透 | 不能推导真实行业占比 |
