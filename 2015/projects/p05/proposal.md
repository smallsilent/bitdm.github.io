---
layout: page
mathjax: true
permalink: /projects/p05/proposal/
---

## 股票数据分析——预测某支股票未来收益

### 成员

- 郝晓鹏  2120141012
-  杜天元  2120140999 
- 李舒扬  2120141020 

### 目标

   通过分析某支股票几年内的交易走向，建立相应数学模型，能够预测未来一段时间内的收益（如涨幅/跌幅能达到百分之多少、收盘价能达到多少、成交量会有何变化等）

### 数据获取方式

国内流行的炒股软件（如同花顺）中有导出历史数据的功能，在软件中便可完成股票数据的获取，不需要使用爬虫脚本。

数据中会包括：开盘价，最高价，最低价，收盘价，涨幅，振幅等数据。


### 数据分析方式

  使用R语言作为数据预测的环境，R语言的TTR包中有大量衡量股票的指标，通过使用合适的指标可以完成我们的预测。

 在模型选择方面，我们打算使用人工神经网络进行建模。

###  变量说明：

在研究的过程中，我们从简单出发，不考虑政策、同类型股票、大盘指数的变化等额外因素，只从该股票本身的每日开盘、收盘价格以及成交量等基本信息入手，建立一个最简单的数学模型。