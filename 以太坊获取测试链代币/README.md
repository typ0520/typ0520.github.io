发起以太坊交易时需要消耗以太币，开发智能合约做测试时如果在主网做测试成本会很高，并且主网的速度也比较慢，以太坊官方考虑到大家的这个需求提供了几条测试链供大家使用，比较知名的有以下这几个

- [**Ropsten**](https://ropsten.etherscan.io/)

以太坊的主测试网，环境最接近主网环境，有实际的雷锋矿工在挖矿，只不过难度会比主网低很多，不过由于 Ropsten 采用与主网完全一样的 PoW 共识，有时也就会和主网一样拥堵，在这条链上做测试更容易测试出智能合约或者dapp里潜在的问题

- [**Rinkeby**](https://rinkeby.etherscan.io/)

用的是 PoA 机制，无需挖矿，所以出块很快而且很稳定

- [**Kovan**](https://kovan.etherscan.io/)

和Rinkeby同样使用的是 PoA 机制

###下面介绍下如何获取这几条链的测试币

######Ropsten

打开这个网址[https://faucet.metamask.io/](https://faucet.metamask.io/)

![faucet_ropsten_1.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_ropsten_1.jpg)

点击**request 1 ether from faucet**按钮会通过web3连接钱包，获取到钱包当前账户(以太坊地址)，我使用的钱包是MetaMask，如果你没有装支持web3访问的钱包，可以参考这篇文章安装
[https://www.jianshu.com/p/a84fe16f1af7](https://www.jianshu.com/p/a84fe16f1af7)

![faucet_ropsten_2.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_ropsten_2.jpg)

点击连接

![faucet_ropsten_3.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_ropsten_3.jpg)

连接成功后会生成一笔交易，交易的hash显示在页面底部

![faucet_ropsten_4.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_ropsten_4.jpg)

等交易确认后一个以太坊就到账了

![faucet_ropsten_5.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_ropsten_5.jpg)

######Rinkeby

Rinkeby获取测试币相对麻烦些，需要注册twitter账号(需要翻墙)

打开这个网址[https://twitter.com/intent/tweet?text=Requesting%20faucet%20funds%20into%200x0000000000000000000000000000000000000000%20on%20the%20%23Rinkeby%20%23Ethereum%20test%20network](https://twitter.com/intent/tweet?text=Requesting%20faucet%20funds%20into%200x0000000000000000000000000000000000000000%20on%20the%20%23Rinkeby%20%23Ethereum%20test%20network)

![faucet_rinkeby_twitter_1.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_rinkeby_twitter_1.jpg)

把推文中0x0000000000000000000000000000000000000000替换成你的地址点击TWEET，发送成功后点击分享图标选择Copy link to Tweet，把推文的链接复制下来

![faucet_rinkeby_twitter_2.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_rinkeby_twitter_2.jpg)

![faucet_rinkeby_twitter_3.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_rinkeby_twitter_3.jpg)

然后打开Rinkeby测试币水龙头网页 [https://www.rinkeby.io/#faucet](https://www.rinkeby.io/#faucet)

![faucet_rinkeby_twitter_4.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_rinkeby_twitter_4.jpg)

把刚才那个推文链接复制进输入框，点击Give me Ether

![faucet_rinkeby_twitter_5.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_rinkeby_twitter_5.jpg)

  根据你的需要选择要多少个代币，要的越多到账越慢😓，到账时间相对其它的测试链很慢，如果着急就用别的链做测试

######kovan

打开这个网址[https://faucet.kovan.network/](https://faucet.kovan.network/)，需要使用github账号登陆

![faucet_kovan_1.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_kovan_1.jpg)

登陆成功后输入以太坊地址，点击发送就好了，转账交易就提交到链上了

![faucet_kovan_2.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_kovan_2.jpg)

![faucet_kovan_3.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_kovan_3.jpg)

同样的等待交易确认就能收到一个以太币了

![faucet_kovan_4.jpg](https://raw.githubusercontent.com/typ0520/typ0520.github.io/master/以太坊获取测试链代币/faucet_kovan_4.jpg)

