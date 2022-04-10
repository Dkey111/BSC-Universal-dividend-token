## 币安链全能分红币



### 功能齐全

- 支持分红币安链的所有代币，例如ETH/DOGE/USDT等
- 一键设置可接受分红的持币数量、分红间隔
- 添加白名单、拉黑地址
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
serviceAddr_: 待定
buyFeeSetting_: [X,X,X,X] (X是数字，也就是百分比，分别对应分红、流动性、市场营销、燃烧)
sellFeeSetting_: [X,X,X,X] 同上
tokenBalanceForReward_: 持有多少代币参与分红，单位是wei，所以数量后要加18个0
```



### TG电报群

https://t.me/+7tvIu5AMs7I3NmU1
