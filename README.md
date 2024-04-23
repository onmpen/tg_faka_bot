## 介绍
这是一个Telegram 发卡机器人，此机器人基于Python开发，在Python 3.6.7测试通过。

## 使用方法
### 安装依赖
`pip3 install -r requirements.txt` 
### 编辑配置
编辑`config.py`文件，根据注释配置参数
### 启动方法
`python3 main.py`

## 功能介绍
### 管理员界面
![](https://s3.jpg.cm/2020/06/29/cwB5y.jpg)
![](https://s3.jpg.cm/2020/06/29/cw0LC.jpg)
![](https://s3.jpg.cm/2020/06/29/cw2bt.jpg)
![](https://s3.jpg.cm/2020/06/29/cwg25.jpg)
![](https://s3.jpg.cm/2020/06/29/cwfNr.jpg)
### 整体功能演示
[GIF演示](https://github.com/lulafun/tg_faka_bot/raw/master/fakabot2.gif)
![](http://kangle.bakbak.cn/fakabot2.gif)
### 数据库
使用sqlite3作为数据库，轻量、便于备份。
### 支付成功跳转页面
可以自定义，本程序判断是否支付成功并不是通过支付回调，而是采用向聚合支付接口轮询实现
### 支付接口
支付接口基于易支付。
为什么选择易支付？因为做易支付的聚合支付比较多，用TG发卡的，不会真有人用自己的实名微信、支付宝收款吧～
由于市面上有许多的易支付版本，虽然接口传参一样，但是有些网站的返回值还是有所不同，目前该程序对我所使用过的易支付站点做了适配，如有不适配的情况，可以积极反馈

## 版本说明
本版本是开源发布的最终版本，很大情况下代码不会再次进行维护更新，此版本的功能对于日常使用来说已经足够

此外还有一个收费版本，相对于此开源版本会有一些功能的增加，日后根据建议反馈会逐渐更新一些更人性化的功能

就目前来说，收费版具有的额外功能是对已经上架的产品定价、描述、使用说明、排序进行更改，以及导出未售出的卡密（同时不会删除商品）

![](https://i.w3tt.com/2020/06/29/OS6eb.jpg)
![](https://i.w3tt.com/2020/06/29/OS2aP.jpg)


