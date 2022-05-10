## 币安链全能分红币



### 功能齐全

- 支持分红币安链的除bnb之外的所有代币，例如ETH/DOGE/USDT等
- 一键设置可接受分红的持币数量、分红间隔
- 批量添加白名单、拉黑地址
- 一键设置买入卖出的分红、回流、营销、销毁的各比例



### 编译/开源须知

```
COMPILER: v0.8.7+commit.e28d00a7.js
Enable optimization: 开启并使用默认值200
Other Settings: default evmVersion, MIT license
```



### 部署参数

contract选择Blocktechnology合约进行部署，Value值200000000000000000（17个0，0.2BNB）

```
name_:  代币名称
symbol_:  代币符号
totalSupply_:  发行量
rewardAddr_:  分红代币的合约，注意一定是币安链上的
marketingWalletAddr_: 市场营销钱包，自己的
serviceAddr_: 0x7Ea95D639c59E5E0Dd4b7f4d62b5558933a84Fd9 （主网依赖合约）
buyFeeSetting_: [X,X,X,X] (X是数字，也就是百分比，分别对应分红、流动性、市场营销、燃烧，参考[1,1,1,2])
sellFeeSetting_: [X,X,X,X] 同上
tokenBalanceForReward_: 持有多少代币参与分红，单位是wei，所以数量后要加18个0
```


### 测试网相关参数

```
薄饼测试网路由，源码676行:0xB6BA90af76D139AB3170c7df0139636dB6120F7e
测试网usdt:0xEdA5dA0050e21e9E34fadb1075986Af1370c7BDb
测试网SHIB: 0x11e815a78Cc41D733Db00f06B3A96074855362CE
测试网依赖合约:0x72519BE1b6fcd1493378e38628ba60Dc34DeB41f
```


### 添加流动性时（加池子）注意要用bnb添加，因为源码的交易对是bnb和部署的代币，更多问题欢迎加TG群讨论



### TG电报群（两个链接均可）

https://t.me/mingchao888

https://ss.transgot.cn/mingchao888
