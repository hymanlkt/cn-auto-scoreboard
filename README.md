# 汽车市场预判记分牌

每个判断都在数据公布**之前**写下并公开，数据公布后由程序自动判对错。

- 网页：https://hymanlkt.github.io/cn-auto-scoreboard/
- 预判清单：[`data/predictions.json`](data/predictions.json)，每条都绑定一个可计算的指标和阈值
- 记分牌：[`data/scoreboard.json`](data/scoreboard.json)，包含命中率、按置信度分组的校准和 Brier 分数
- 数据健康：[`data/health.json`](data/health.json)，包含新鲜度、两源交叉验证和防护拦截记录
- 市场概览：[`data/market.json`](data/market.json)，大盘、新能源渗透率、品牌前十份额、价格段结构

**怎么验证"事前"**：看本仓库的提交历史。每条预判第一次出现的提交时间，都早于对应月份数据的公布日。

数据来源：懂车帝、乘联会、盖世汽车、汽车之家。本仓库只包含作者计算的聚合结论，不提供车系级明细或第三方榜单；由程序自动生成，请勿手动修改。内容不构成任何投资建议。
