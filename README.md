[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
# flink 源码解读


Flink是大数据处理领域最近很火的一个开源的分布式、高性能的流式处理框架，其对数据的处理可以达到毫秒级别。本文以一个来自官网的WordCount例子为引，全面剖析flink source code , 阐述flink的核心架构及执行流程，希望读者可以借此更加深入的理解Flink逻辑。

如果有任何问题，欢迎随时交流！

//todo 2019.03
之前由于工作繁重，不得不提前结束整个解读，近期我会增加执行计划部分和代码生成部分的解读，敬请期待！
