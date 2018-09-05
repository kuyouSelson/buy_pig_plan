# buy_pig_plan | 买猪计划

#### 写在前面

以前，有个人经常给我女朋友打骚扰电话,这家伙实在太可气了，得给他点教训，让他知道骚扰电话的厉害。于是有了这个程序。
在持续的攻击一段时间后我也悄悄的对目标做过一些回访，看看用户体验，顺便记录下来看看攻击效果：

|     时间   |                        目标状态                              |
|------------|--------------------------------------------------------------|
| 2018.08.18 | 佯装某机构人员电话回访,对方态度**不耐烦**,没讲几句就挂断电话 |


#### 项目介绍

> 买猪计划：一个电话攻击、留言攻击的工具
> 为什么叫`买猪计划`呢？因为我最开始是通过猪场的网站发起电话攻击的，所以取名`买猪计划`。

这是一个用来对目标发起电话攻击的项目。坚持定时服用，这个项目会产生最漫长的、最有效的攻击。项目主要是通过两种方式产生两种不同效果的攻击。

##### 电话回拨系统（实时攻击）
这种方式利用网站常用的电话回拨系统发起攻击，目标一般会在攻击发出几分钟内收到电话。电话会由不同的号码打出（一般是网站的电话，所以收集的网站越多越好，目前支持1W+网站），所以即使目标拉黑几个也没有多大影响。对于这种攻击建议定时发起，比如深夜、凌晨。

##### 留言系统（非实时攻击）
这种方式利用网站的留言系统发起攻击，目标何时、收到何种方式的攻击取决于看到留言的人怎么处理。因为我们留下了手机号，所以看到留言后一般都是电话联系。这种方式很有意思，有点余音绕梁的感觉。这种攻击全天都可以发起，而且攻击越久持续效果越好。

两种方式都很有意思（跟短信轰炸比起来好多了），优点也很明显：

- **匿名**。除了**会带有IP信息**外，不会带有其他与你有关的信息
- **简单**。动动小手跑跑程序，比自己戳来戳去半天才发了几个骚扰短信简单多了
- **高效**。比起发短信攻击来说，直接电话攻击何止是高效啊，简直就是高效啊喂
- **零成本**。除了费点电费跑跑程序外你好像也没其他损失啊，我说零成本也不过分吧
- **数据多**。目前支持1.2W+网站电话回拨攻击、1.7W+网站留言攻击，而且还在不断更新
- **可重复**。对于电话回拨系统攻击的方式，可以经常跑一跑，即使是同一批网站多跑几次也是没有关系的
- **可放大**。不管是电话攻击还是留言攻击，都存在对方做电话回访的可能性，所以，你发动的可不仅仅是一次攻击哦

#### 安装教程

- 本项目依赖[`chromium(需要梯子)`](https://download-chromium.appspot.com/),需要手动下载安装.
- 下载本项目

```sh
git clone https://github.com/aqiongbei/bomer.git
```

- 安装依赖

```sh
npm install
```

- 启动项目
```sh
npm run start
```


#### 使用说明

1. 配置文件
2. 网站源切换

#### 实现功能

- 电话攻击
- 留言攻击
- 定时任务
- 任务报告
- 任务统计
- 随机网站攻击
- 100000+网站支持
- 攻击参数可配置

#### TODO

- log记录
- 短信攻击
- 邮件接受报告
- 数据存入数据库