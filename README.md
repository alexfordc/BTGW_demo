# BTGW_demo
#### BTGW数字货币交易网关服务器运行包（Demo）

　BTGW_demo是蓝目数字货币交易网关服务器运行包Demo，用于演示蓝目交易网关，以统一化的交易数据格式，执行各个交易所的委托下单、委托撤单、交易记录查询等API接口，为数字货币交易者屏蔽各个交易所API的巨大差异，让交易者们更专注于策略和执行。<br>
　目前支持的数字资产交易所包括：bitfinex, kraken, bitstamp, bittrex, okex, huobi, binance, bitmex,zb, poloniex, bithumb. 提供详细的API访问接口文档，以及针对python, C++ 和java 的客户端访问源码。由于BTGW_demo是demo版，只支持okex的交易，如需连接其他交易所，请联系blueye_info@163.com或登录 [官网](https://www.blueye.info) 咨询<br>
　蓝目数据提供了全球各大主流数字资产交易所的全部品种的实时交易行情和各类历史数据，供专业的投资机构和个人宽客使用。数据包含了实时数据ticker, 深度数据depth, 各周期历史kline，并且提供了各个交易所的委托下单、委托撤单、交易信息查询等接口。<br>
　<br>
　[官方网站](https://www.blueye.info)

#### 使用对象
　数字货币数据分析师<br>
　数字货币量化交易的个人或团队<br>
　对数字货币交易感兴趣的机构<br>
　分析行情数据的个人或团队<br>
　正在学习数字货币交易的人<br>
 
#### 使用前提
　windows 操作系统。<br>

#### 下载安装
1. 下载安装BTGW_demo。下载TEmu_demo客户端。

2. 在acc_key.json配置文件设置好自己的okex交易所API Key和Secret Key。

3. 在命令行提示符进入BTGW_demo目录，运行BTGW.exe variables.json。

6. 在命令行提示符进入TEmu_demo目录，运行TEmu.exe 127.0.0.1 1819，连接BTGW_demo。

7. 按照TEmu测试方法和数字货币网关消息定义，发送交易指令。

####  交易测试

[TEmu测试方法.txt](./TEmu测试方法.txt)


####  消息格式文档

[数字货币网关消息定义](./数字货币网关消息定义-20180622.docx)
