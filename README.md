# Ethereum Anomaly Investigation Agent

本仓库用于两位本科生共同开发“以太坊链上异常调查 Agent”。

项目目标：选择一种适合多步调查的链上异常现象，构建一个带网页界面的 Agent。输入地址或交易后，Agent 能查询链上数据、沿线索继续调查，并展示关键交易、关联地址、证据链接和分析结论。结论需要有链上证据支持；证据不足时应明确说明不确定性。

参考资料：

- RiskTagger: https://arxiv.org/abs/2510.17848
- Etherscan API: https://docs.etherscan.io/api-reference/endpoint/txlist
- Forta labels: https://github.com/forta-network/labelled-datasets
- PTXPhish: https://github.com/blocksecteam/PTXPhish
- Poison-Hunter: https://github.com/DS2L/Poison-Hunter
