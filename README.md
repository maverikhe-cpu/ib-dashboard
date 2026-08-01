# IB 持仓看板

个人 Interactive Brokers 持仓跟踪看板的**静态构建产物**,由主仓库
`IB跟踪/dashboard` 的 `npm run build` 生成,经 `deploy.sh` 手动推送。

- 数据来源:Interactive Brokers Activity Flex 报告
- 源码与取数流水线位于私有仓库,不在此公开
- 数据为聚合摘要(净值/持仓/股息),原始交易明细不公开

站点地址:<https://maverikhe-cpu.github.io/ib-dashboard/>