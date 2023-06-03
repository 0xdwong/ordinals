# 序数表示形式

## 序数有几种不同的表示形式

- 整数表示法： `2099994106992659` 序号，按照聪被挖出的顺序分配
- 十进制表示法： `3891094.16797` 第一个数字是聪被挖出的区块高度，第二个数字是聪在区块内的偏移量
- 度数表示法： `3°111094′214″16797‴`
    
    ```jsx
    A°B′C″D‴
    │ │ │ ╰─ Index of sat in the block
    │ │ ╰─── Index of block in difficulty adjustment period
    │ ╰───── Index of block in halving epoch
    ╰─────── Cycle, numbered starting from 0
    ```
    
- 百分位符号表示法： `99.99971949060254%` 。 satoshi 在比特币供应中的位置，以百分比表示。
- 名称表示法： `satoshi` 。使用字符 `a` 到 `z` 的序数编码。

## 稀有度级别

按度数表示法，产生了稀有度概念

- `common` ：任何不是其块的第一个 sat 的 sat
- `uncommon` : 每个block的第一个sat
- `rare` : 每个难度调整期的第一个sat
- `epic` : 每个减半周期的第一个 sat
- `legendary` : 每个周期的第一个 sat
- `mythic` : 创世块的第一个 sat