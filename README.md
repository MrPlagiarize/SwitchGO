# 关于FGO国服B站安卓 1.20.1 阿仗/switch版本的声明
利益相关：本人不制作、发布或售卖科技及相关产品。请支持正版，别问我任何技术问题或求啥东西，都是我家猫xjb敲的。

讲下事情发生过程
首先认识switch是在某科技交流群里 当时随口说了自己有IOS的key 就被加了好友聊了聊我也相信了switch 是个同样喜欢游戏和技术研究的同道中人。

![Alt text](https://github.com/MrPlagiarize/SwitchGO/raw/master/img/%E6%88%AA%E5%9B%BE.png)


然后接下来的1.17.1 dump 修复 一起研究的时候也是很开心的研究过程 但是1.20.1开始事情发生了变化。首先switch直到版本更新也没能自己拿到关键的key（下图是我给他key和我的dump的截图），他手里的版本是我运气好拿到的一个加密有问题的客户端dump出部分解密的dll。众所周知的脱机事件，我没能成功阻拦switch发布脱机，也有大佬指出switch 上了个几k的壳子之类的事情。至此我仍然没有怀疑过他打算商用。爱装x搞事啥的也不是事谁还没年轻过下次不搞了还是兄弟，所以继续我的研究 。

![Alt text](https://github.com/MrPlagiarize/SwitchGO/raw/master/img/%E6%88%AA%E5%9B%BE2.png)

终于在1.20.1发布前一天我通宵探究解开了完整的dll加密。接着在1.20.1发布后花了几小时解开了1.20.1的dll加密。这也就是你们现在看到的阿仗版客户端的核心dll来源。
 
![Alt text](https://github.com/MrPlagiarize/SwitchGO/raw/master/img/%E6%88%AA%E5%9B%BE3.png)


这图是我当时给switch dll时候的截图。
 
 ![Alt text](https://github.com/MrPlagiarize/SwitchGO/raw/master/img/%E6%88%AA%E5%9B%BE4.png)


别的不说咱的信任就这么不值钱吗。你告诉我8k买的加密，那你是要卖出去几百份？这就是你说的帮朋友打不搞事？作为一个安心研究技术玩玩游戏的人本来很开心能遇到同道中人。但是这份信任被这样使用我心情实在不好过也实在是无法忍受，沟通过后switch并没有为这样的行为做出任何致歉表示，你们天天喊盗卖该打，那这样又算啥？说啥作者说不包更新?我连知道都不知道你做这事情。
 
![Alt text](https://github.com/MrPlagiarize/SwitchGO/raw/master/img/%E6%88%AA%E5%9B%BE5.png)

 
截至到我发帖为止足足20多小时 switch对此事件并没有给出任何表态。

ps：据说事后还甩锅给了perfare大佬来我们看看他说怎么评价大佬的blog的

![Alt text](https://github.com/MrPlagiarize/SwitchGO/raw/master/img/%E6%88%AA%E5%9B%BE6.png)

在此声明本人对于国服加密的探究行为仅限于学习研究和个人娱乐不存在牟利和传播企图并且已经删除全部相关代码终止关于FGO加密研究。阿仗/switch version造成的相关损失和法律责任与本人无关。

关于休闲游戏壳子我也实在不想说啥 连method_code加密算法都是直接搬的xtea源码...
int key[] = {0x32220201,0x4597af75,0x30202a6,0x56783490};
嗯 就是这样
