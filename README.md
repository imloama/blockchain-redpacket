# blockchain-redpacket
区块链币红包应用，暂支持恒星

## 简介

区块链有相对较高的门槛，通过发红包的形式，向普通大众传递相关理念，也可能有一些应用场景，发红包数据直接上链，用户可以通过发红包，设置相应的关键信息，保存到链上，比如给家人发生日红包，祝福信息都可以保存到链上。

实现的功能:
1. 发红包：用户有私钥，执行相应的参数提交到后台服务器，由后台服务器提交上链
2. 生成待抢红包：后台生成随机或定额红包，待领取
3. 抢红包：用户通过地址抢红包
4. 退红包：如果红包有未领取完的余额，直接退到发包者账户
5. 统计分析
