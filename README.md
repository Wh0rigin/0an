# 0an
我有一个想法，然后我想把他记录下来并想加以实现！

## 前言：
在思考毕设的时候突发奇想，想到将区块链技术与物联网相互结合，完成物联网关键信息存储链。以防止对链路上的数据的修改，保证数据的唯一性，与安全性。


## 主要语言
由golang作为主要生产语言，http接收数据信息，并由内部集群进行加密计算。为何要统一数据加密源？就是为了控制区块链矿池风险。矿池控制了大量算力，一旦某矿池超过50%，它就有了作恶的能力。对此进行数据的集群去中心化


## 应用场景
银行等高保密度的入侵警告，通过区块链保存，以防黑客篡改

## 开发队列(详细看/dev分支),后期还会将新的想法加入开发队列！
- [ ] 链体开发
- [ ] HTTP对外接口
- [ ] 数据持久化
- [ ] 无数据时链路过短，从而发生的可能性篡改？（需要对内鬼特攻

## 声明
无论如何现在的解决方案是极其简单的，但无论该项目的有用与否，总之是想用在毕设，先把毕设干了吧！

## 可能性
为解决链体过短而导致的容易修改问题，是否可以在生成链时指定安全等级先以祖父区块为头点创建多个随机数为数据体的子祖父节点，以保证链条长度

## 讨论
email 805935229@qq.com
