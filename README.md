# 股票公式的解析器

## 1. 为什么要写这玩意
主要配合我自己量化交易使用，目前使用golang来做量化交易语言。很多交易信号都是通过公式来计算的，如果用golang硬编码这些公式，会非常不方便，
所以直接写一个解释器。

## 2. 公式的语法
支持同花顺/通达信的公式语法，但是不支持所有的函数，只支持一部分函数，后续会慢慢增加。

## 3. 目前支持的范围
- [x] 基本的数学运算
- [ ] 逻辑运算
- [ ] 函数
  - [x] HHV
  - [x] LLV
  - [x] MA
  - [x] REF
- [X] 变量