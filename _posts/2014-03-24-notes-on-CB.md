---
layout: post
title: 可转债计算细节
comments: true
categories:
- investment
tags:
- 可转债
- 转股
---

转债的交易记录以及交割过程比股票要稍显复杂，但是，弄清楚这个过程也很有必要。以2014年3月19号的交易为例。

## 转债转股是如何完成和计算的？

在3月19号早上，以125.5的价格买入100张中鼎转债，手续费12.5元，收盘之前执行转股，于是，我们得到转股之后的股票是1440股，价格为市场价格，同时得到现金6.41元。那么，这里的1440和6.41元是怎么来的呢？

解释一下：每张中鼎转债的面值是100元，转债转股条款中约定的转股价格是6.94元，则100张中鼎转债对应的正股数目是100/6.94*100=1440.922，整数部分即1440以中鼎股份的形式交割给我们，这就是实际得到的股票数目。不足一股的部分，即0.922乘以转股价格之后以现金形式返给我们，我们得到现金是6.94×0.922=6.41元。

## 如何计算转股之后的盈亏平衡价格

如果没有开通融券业务，则买入转债之后，转股收益取决于第二天的正股价格。在给定转股价的情况下，转债价格和正股价格是线性关系，对应到上面的例子就是：

转债价格=100/6.94*正股价格

或者：

转债价格=14.41*正股价格

于是有，125.5的买入价格对应正股盈亏平衡价格为125.5÷14.41=8.71。也即，如果第二天的股票价格高于8.71，我们以125.5的价格买入的这笔中鼎转债在转股之后就是盈利的。

（备注：未考虑交易费用）


