# SOLANA上的资金流

![如果时间就是金钱，为什么我们不能连续获得报酬？](https://miro.medium.com/max/1400/0\*BW3Ty\_J7xDoKloEE.jpeg)

自从货币进入社会用于商业和贸易后，劳动力立即成为最具交换属性的资产。我们所说的**劳动**，是指**时间**。然而，今天用时间换取金钱的大多数劳动力正在做一个可怕的交易；一个具有巨大劣势的交易：

> 出售自己的时间换取金钱的人向他们的交易方提供无息贷款。

现在的工人不会过多考虑这种不利的交易，人们以 “这就是工作 ”的心态轻视它，主要是因为几个世纪以来没有更好的选择。\
让我们来更深入地解释一下。

### 不公平的做法 <a href="#79f6" id="79f6"></a>

如果时间就是金钱，为什么我们不能连续获得报酬？

**时间**是一种连续的媒介，因为它**奔流不止**。然而，**付款**是一种预定的媒介，而且**需要有人来触发它**。\
大多数受薪雇员的工资是按月或按双周支付的。也就是说，他们工作了30天，然后才会得到报酬。这种劳动制度的背后隐藏着一个肮脏的小秘密👇

> **雇员**在他们工作的每一秒钟给**雇主**提供0%的利息贷款，直到他们在月底获得全额工资。

你可能认为这不是一个大问题，直到你看一下原始数字，其中显示，如果他们只是对这些贷款收取通货膨胀率而不是0%，（全世界）普通工人将能够多带回家446美元。这在世界大多数地区都是一笔巨大的数目，是为雇主的利益而省下的钱，相应的，雇员的利益则被牺牲了。**这是为了世界上的每一个工人！**

![](https://miro.medium.com/max/700/0\*2M0flTxU7fPYWzJl.png)

### 好吧，我明白了，这确实是个大问题……现在怎么办？ <a href="#3d0a" id="3d0a"></a>

这是一个巨大的问题，使用传统的金融体系几乎不可能解决。处理这个问题的公平途径是：

> 一秒钟的工作就是一秒钟的收入

然而，这种方法需要一个金融基础设施，使其有可能在每个工人实际工作的每一秒后立即支付他们的工资，以避免自由资金的难题。\
用传统的金融来探索这种可能性是不可能的。你需要一个能够做到这些的的薪资系统：

1. 根据工人的合同费率向其支付报酬
2. 对工人工作的每一秒钟都给予补偿
3. 统一地补偿工人（即在全球范围内进行，不受管辖，因为时间不受当地法律的限制）

今天，世界上的货币转移支付机构和银行都被束缚在围墙花园里，比如SEPA、ACH、电汇，甚至像PayPal、Zelle等较新的货币转移支付机构，最多只能让用户在花园里相对轻松地相互付款，但这就是魔法的终点。即使像Xero和QuickBooks这样领先的工资系统也受到这些其他中心式货币转移支付系统的限制，有很多制约因素。

如果你是一个向全球受众提供技能的顾问或服务提供商，你必须依靠许多不同的围墙花园和高昂的费用来获得报酬（Payoneer，World Remit，等等）。如果你是一个拥有在不同国家工作的远程员工的雇主，工资将会是你最大的噩梦之一…直到现在。

### 一个全新的世界 <a href="#7ec9" id="7ec9"></a>

> A new fantastic point of view\
> No one to tell us, “No”\
> Or where to go\
> Or say we’re only dreaming…

等等，等等……发错了，阿拉丁……虽然我们下面要展示的东西感觉完全是一个[魔法](https://en.wikipedia.org/wiki/Genie\_\(Disney\))才能实现的愿望。\
区块链技术和DeFi在这里为货币传输者提供了一个新的时代。欢迎来到 “资金流时代”。\
资金流是在一段时间内持续支付的概念，就像水流一样。思考这个问题的最佳方式是，SEPA和ACH系统是VHS磁带和DVD，货币流是Netflix和Spotify。

![](https://miro.medium.com/max/700/0\*1RkucoAF1cb\_bgPz.png)

资金流允许任何两方定义一个合同（流），该合同简单地规定：

1. 资金从甲方流向乙方的速率
2. 暂停/关闭/退出流动的权限和条件（干涸、充值等）。

[Mean协议](https://en.wikipedia.org/wiki/Genie\_\(Disney\))为[Solana](https://solana.com)的开发者提供了一个可以在他们的应用程序中利用的资金流程序。使用案例非常多，包括工资、停车计时器、退休基金、租金收取等等。所有的用例都是以时间换金钱的隐性交换。

去[阅读白皮书](https://docs.meanfi.com/platform/specifications/money-streaming-protocol)中关于资金流的完整规范，其中有很多说明性的使用案例。

如果你想在你自己的DApp中利用资金流，最简单的方法是通过运行

> npm i @mean/money-streaming

你可以在[这里](https://github.com/mean-dao/mean-sdk)查看代码，也可以在这里[查看](https://docs.meanfi.com/platform/developers)开发者文档。

### MeanFi的资金流 <a href="#c331" id="c331"></a>

你可以在MeanFi.com上的一个web3应用程序中体验资金流程序的实际使用。我们已经在那里实现了两个用例，你今天就可以开始使用。

\#1）发送重复性付款。在这个用例中，你可以以重复的方式给家人或朋友送钱（又称汇款），比如每月一次，或每周一次，来创建一个资金流。设置一次你就可以忘记它。不再去西联汇款或速汇金，不再设置闹钟以免忘记，不再有妈妈向你要钱的尴尬时刻……所有这些都是自动发生的。

打开 [MeanFi](https://app.meanfi.com) → Transfers →把 “One Time Payment” 换成 “Repeating Payment”

![](https://miro.medium.com/max/700/0\*vMhJexXBza2EFxEH.png)

\#2）工资/薪金。顾名思义，这是为企业支付他们的雇员，或承包商想要执行其服务的付款。

访问 [MeanFi](https://app.meanfi.com) → Services → Payroll

![](https://miro.medium.com/max/700/0\*z5u3JF-9s\_kmiRyL.png)

在你创建了你的重复付款或工资单后，你可以在你的转账标签下找到流出的资金流。根据你过去的转账和资金流，你会看到资金从账户中流出（或流入）并实时进入（或流出）收款人的账户。

所有资金流（发送和接收）将显示在转账项下。

![就像这样](https://miro.medium.com/max/480/0\*\_LPMCVNzfXhhaPEI.gif)

### 总结 <a href="#3234" id="3234"></a>

资金流是令人敬畏的。它们允许你通过实时收集资金来最大化时间产出。由于Solana的亚秒级出块时间和完整性，任何人都可以在几乎无限的使用情况下享受实时资金流。\
我们期待着与Solana生态系统的开发者合作，在他们自己的应用程序中实现货币流。

> 变成水吧，我的财富
>
> \-李小龙

如果他还在的话他一定会这么说的… 真实的故事 😜

每周关注我们的实时工作进展, 加入区块链革命通过访问我们的 [website](https://meanfi.com), 加入[Mean DAO Discord](https://discord.com/channels/850556915670450197/887319521424195645/887319736231284746), 关注推特 [@MeanFinance](https://twitter.com/meanfinance) 。