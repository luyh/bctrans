文章来源:
https://medium.com/eosio/dawn-3-0-alpha-announcement-7f8b1bd74364

DAWN 3.0 Alpha Announcement

DAWN 3.0 Alpha 公告

Originally published on steemit.com on 26 January 2018.

原文于2018年1月26日发表于steemit.com

![EOS DAWN 3.0](https://cdn-images-1.medium.com/max/800/0*99bwkzCu517eJ3tZ.png)

> As many in the EOS.IO development community are aware, we’ve been working since December on merging two lines of development, Dawn 2.x and Dawn 3.0.As many in the EOS.IO development community are aware, we’ve been working since December on merging two lines of development, Dawn 2.x and Dawn 3.0. The merged code base is now stable enough to make public as an Early Alpha and will now become our Github master branch. The prior master will be renamed “dawn-2.x” and will continue to be available as a non-master branch.

正如EOS.IO的开发者社区意识到的，我们在12月将开发的两条分支：黎明2.x 和 黎明3.0.合并的代码已经足够稳定，可以作为早期公测Alpha版本，并将变为Github上的主分支。先前的主分支将被重命名的“dawn-2.x”(黎明2.x),将继续以非主分支的形式存在。

> Community developers will notice that the next time they “git pull” from Master, they will obtain the new Dawn 3.0 code. Those wishing to continue to pull the Dawn 2.x code that connects to the current TestNet can do so by following instructions in the new readme.md, being made available at the same time as the re-mastering.

社区开发者在下一步拉取主分支时，他们会意识到得到的将是黎明3.0主分支的代码。现在的测试网络使用的是黎明2.x的代码，在切换主分支时将更新readme.md说明文档,开发者们可以按照新的说明文档中的方法拉取到黎明2.0的代码。

> Please note that the Dawn 3.0 code is still in Early Alpha and is not compatible with the current block.one-provided public TestNet; it will not be available in a public TestNet until the end of Q1 2018. In the interim, developers may create their own testnets with the new Dawn 3.0 code. As a reminder, Dan Larimer and the development team have changed the way we forecast development. This means we won’t be announcing the date for the Dawn 3.0 Testnet until the timeline is close enough for us to have high confidence in its capabilities.

请注意，黎明3.0的代码仍然是早期的Aopha版本，并且与现在block.one公司支持的公测网络并不兼容，直到在2018年第1季度末，公测网络才将支持黎明3.0的代码。在此期间，开发者会创建他们自己的支持Dawn 3.0代码的测试网络。提醒一下，Dan Larimer和开发团队已经切换了早期的开发模式，这意味着，直到我们对Dawn 3.0的性能有足够高的信心时，我们才会声明Dawn 3.0 测试网络的发布时间。

> The current public TestNet at “https://testnet1.eos.io” will continue to run the Dawn 2.x software until the release of the Dawn 3.0 Testnet, and will then be retired.

当前的测试网络 “https://testnet1.eos.io” 将继续运行黎明2.x的软件，直到黎明3.0测试网络发布才将退出。

> Smart contracts written for the Dawn 2.x codebase will need to be revised to work on the new 3.0 codebase and take advantage of the new features.

为黎明2.x代码写的智能合约需要重新修改，才能充分发挥3.0的代码新的特性。


> Major changes in Dawn 3.0 include changing “eos” to “eosio” in all locations throughout the code. We have also renamed “message” to “action”, and removed the need for developers to manually specify ‘scope’; all scope specification is now automated.

黎明3.0的主要改变包括：所有代码中的"eos"改为"eosio"，我们同样将“message”重命名为“action”，移除开发者需要手动指定“scope”(范围？)，所有范围指定均已自动化。

> Additional new features in the Dawn 3.0 Alpha Release include: deferred transactions, staking pools, a new currency contract, and a new emerging token standard. A complete list of new features will be included in the 3.0 Final Release notes, expected by the end of Q1 2018. A complete list of EOS.IO Software Releases can be found here:
https://github.com/EOSIO/eos/wiki/Releases

其他黎明3.0 Alpha发布的新特性包括：延迟交易，staking pools，新的货币智能合约，新的紧急通证标准。2018年Q1季度末，预计发布的3.0版本最终发布日志中将包含完整的新特性列表。EOS.IO软件发布的完整列表，可以在这里查到：https://github.com/EOSIO/eos/wiki/Releases
