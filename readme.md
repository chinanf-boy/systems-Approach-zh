# 系统方法 [![translate-svg]][translate-list]

[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list

「 计算机网络：系统方法 」

[中文](./readme.zh.md) | [english](https://github.com/SystemsApproach/book)

> 哦, 太多了， 只作为 浅浅看看

---

## 校对 🀄️

<!-- doc-templite START generated -->
<!-- repo = 'SystemsApproach/book'  -->
<!-- commit = '48d05209ac2b99da2b941e70a50ae4478909c9ec' -->
<!-- time = '2018 8.24' -->
翻译的原文 | 与日期 | 最新更新 | 更多
---|---|---|---
[commit] | ⏰ 2018 8.24 | ![last] | [中文翻译][translate-list]

[last]: https://img.shields.io/github/last-commit/SystemsApproach/book.svg
[commit]: https://github.com/SystemsApproach/book/tree/48d05209ac2b99da2b941e70a50ae4478909c9ec

<!-- doc-templite END generated -->

### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[help me live , live need money 💰](https://github.com/chinanf-boy/live-need-money)

---

### 目录

<!-- START doctoc -->
<!-- END doctoc -->


# 序言

此站点包含源文本*计算机网络: 一种系统方法*现在可用的条件下[创作共享 (CC 4) ](https://creativecommons.org/licenses/by/4.0)许可证. 社区被邀请在相同的条件下做出修正ㄡ改进ㄡ更新和新材料. 

像许多开源软件项目一样,这个软件已经被限制了一次内容: 第五版*彼得森与Davie*受爱思唯尔的版权保护. 我们希望,开放源码这种材料将使它广泛可用,并作为新内容的吸引者: 更新已经存在的内容,扩展它以涵盖新的主题,并增加额外的教学附带文本. 

最初,我们将为返回的贡献发挥编辑作用 (策划和措辞) ,但我们的计划是与致力于项目成功的其他人分享项目的所有权. 

如果你利用这项工作,属性应该包括以下信息: 

> *计算机网络: 一种系统方法\
> 作者: Larry Peterson和Bruce Davie\
> 版权所有: 爱思唯尔,2012\
> 来源: [HTTPS://GITHUB/COM/SCORSH方法](https://github.com/SystemsApproach)\
> 许可证: [CC 4](https://creativecommons.org/licenses/by/4.0)*

## 读Book

这本书的在线版本发表在[HTTPS://Boo.StaseRealAcc.Org](https://book.systemsapproach.org).

## 建书

源内容被组织成每个章节的Git存储库,每一个都集中在一个主要的网络主题上 (例如,*网络互连*,*拥塞控制*) "根"回购协议[这一个](https://github.com/SystemsApproach/book)包含可用于创建完整图书的GITBook文件. 要构建一个Web可查看的版本,首先需要安装几个软件包: 

-  [GITBook工具链](https://toolchain.gitbook.com/setup.html)
-  [JS包管理器](https://www.npmjs.com/get-npm)

然后下载以下内容: 

```shell
mkdir ~/systemsapproach
cd ~/systemsapproach
git clone https://github.com/systemsapproach/book.git
cd book
git submodule init
git submodule update
```

要构建本书的Web版本,只需键入: 

```shell
make
```

如果一切顺利,你将能够在浏览器中查看这本书. `localhost:4000`.  (如果一切都不顺利,你可以试试打字. ) `make`第二次. 

您还可以构建该书的其他版本 (例如,pdfㄡe book) ,但是这样做需要安装其他包,正如在[GITBook工具链](https://toolchain.gitbook.com/ebook.html)站点. 

## 如何投稿

我们希望,如果你使用这种材料,你也愿意贡献回来. 如果您是新的开放源代码,您可以查看此[如何为开源提供贡献](https://opensource.guide/how-to-contribute/)指南. 除此之外,你还可以了解帖子. *问题*您希望看到的地址,并发出*拉动请求*将你的改进归入Github. 

如果你想贡献任何补丁或新材料,你需要签署一个[捐助者许可协议 (CLA) ](https://github.com/SystemsApproach/book/blob/master/CLA.zh.md). 当你第一次提出拉请求时,会提示你在CLA上签名. 

CLA非常简单: 它确立了 (a) 您有权利贡献您正在贡献的内容,以及 (b) 您所贡献的内容对于相同条件下的其他所有人都是可用的[抄送](https://creativecommons.org/licenses/by/4.0)作为现有内容的术语. CLA有一点不同寻常,因为它明确地宣布了Elsevier的权利 (这和每个人的权利一样) ,但这确实表明他们打算继续根据教材出版教科书. 

你也应该熟悉自己. [投稿指南](https://github.com/SystemsApproach/book/blob/master/CONTRIBUTING.zh.md). 作为第一步,我们建议您检查,看看是否有新的文本,你想提交通过我们`MarkDownLint`测试. 要做到这一点,运行

```shell
cd ~/systemsapproach
make lint
```

如果你想做出贡献并寻找需要注意的东西,请参阅当前[项目委员会](https://github.com/orgs/SystemsApproach/projects/). 我们还想扩展主题集/章节,超出从第五版继承的初始集,所以如果你有想法,我们很想听听你的. 发送电子邮件到`discuss@systemsapproach.org`或者更好,[加入论坛](https://groups.google.com/a/systemsapproach.org/forum/#!forum/discuss).

最后,正如这是一个持续的努力,我们将尝试记录和跟踪我们的. [进步](https://github.com/SystemsApproach/book/blob/master/status.zh.md). 现在,把这看作是穷人的发行说明. 

## 加入我们

我们希望你能从中得到价值*计算机网络: 一种系统方法*多年来,我们热切希望你能加入我们的新事业. 

Larry Peterson与Bruce Davie\
2018年8月

# 总结

-  [ ] [序言](README.md)
-  [ ] [第1章: 基金会](https://github.com/chinanf-boy/systems-Approach-foundation-zh/blob/master/problem.zh.md)
    -  [ ] [1.1应用](https://github.com/chinanf-boy/systems-Approach-foundation-zh/blob/master/applications.zh.md)
    -  [ ] [1.2要求](https://github.com/chinanf-boy/systems-Approach-foundation-zh/blob/master/requirements.zh.md)
    -  [ ] [1.3架构](https://github.com/chinanf-boy/systems-Approach-foundation-zh/blob/master/architecture.zh.md)
    -  [ ] [1.4软件](https://github.com/chinanf-boy/systems-Approach-foundation-zh/blob/master/software.zh.md)
    -  [ ] [1.5性能](https://github.com/chinanf-boy/systems-Approach-foundation-zh/blob/master/performance.zh.md)
    -  [ ] [1.6总结](https://github.com/chinanf-boy/systems-Approach-foundation-zh/blob/master/summary.zh.md)
-  [ ] [第2章: 直接连接](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/problem.zh.md)
    -  [ ] [连接的2.1个视角](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/perspective.zh.md)
    -  [ ] [2.2编码](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/encoding.zh.md)
    -  [ ] [2.3框架](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/framing.zh.md)
    -  [ ] [2.4错误检测](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/error.zh.md)
    -  [ ] [2.5可靠传输](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/reliable.zh.md)
    -  [ ] [2.6多址网络](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/ethernet.zh.md)
    -  [ ] [2.7无线网络](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/wireless.zh.md)
    -  [ ] [2.8总结](https://github.com/chinanf-boy/systems-Approach-direct-zh/blob/master/summary.zh.md)
-  [ ] [第3章: 互联网络](https://github.com/chinanf-boy/systems-Approach-internetworking-zh/blob/master/problem.zh.md)
    -  [ ] [3.1开关桥接](https://github.com/chinanf-boy/systems-Approach-internetworking-zh/blob/master/switching.zh.md)
    -  [ ] [3.2个基本的互联网络](https://github.com/chinanf-boy/systems-Approach-internetworking-zh/blob/master/basic-ip.zh.md)
    -  [ ] [3.3路由](https://github.com/chinanf-boy/systems-Approach-internetworking-zh/blob/master/routing.zh.md)
    -  [ ] [3.4实施](https://github.com/chinanf-boy/systems-Approach-internetworking-zh/blob/master/impl.zh.md)
    -  [ ] [3.5总结](https://github.com/chinanf-boy/systems-Approach-internetworking-zh/blob/master/summary.zh.md)
-  [ ] [第4章先进的网络互连](https://github.com/chinanf-boy/systems-Approach-scaling-zh/blob/master/problem.zh.md)
    -  [ ] [4.1全球互联网](https://github.com/chinanf-boy/systems-Approach-scaling-zh/blob/master/global.zh.md)
    -  [ ] [4.2组播](https://github.com/chinanf-boy/systems-Approach-scaling-zh/blob/master/multicast.zh.md)
    -  [ ] [4.3多协议标签交换](https://github.com/chinanf-boy/systems-Approach-scaling-zh/blob/master/mpls.zh.md)
    -  [ ] [4.4移动设备之间的路由选择](https://github.com/chinanf-boy/systems-Approach-scaling-zh/blob/master/mobile-ip.zh.md)
    -  [ ] [4.5总结](https://github.com/chinanf-boy/systems-Approach-scaling-zh/blob/master/summary.zh.md)
-  [ ] [第5章: 端到端协议](https://github.com/chinanf-boy/systems-Approach-e2e-zh/blob/master/problem.zh.md)
    -  [ ] [5.1简单解复用器 (UDP) ](https://github.com/chinanf-boy/systems-Approach-e2e-zh/blob/master/udp.zh.md)
    -  [ ] [5.2可靠字节流 (TCP) ](https://github.com/chinanf-boy/systems-Approach-e2e-zh/blob/master/tcp.zh.md)
    -  [ ] [5.3远程过程调用](https://github.com/chinanf-boy/systems-Approach-e2e-zh/blob/master/rpc.zh.md)
    -  [ ] [5.4实时应用的传输 (RTP) ](https://github.com/chinanf-boy/systems-Approach-e2e-zh/blob/master/rtp.zh.md)
    -  [ ] [5.5总结](https://github.com/chinanf-boy/systems-Approach-e2e-zh/blob/master/summary.zh.md)
-  [ ] [第6章: 拥塞控制和资源分配](https://github.com/chinanf-boy/systems-Approach-congestion-zh/blob/master/problem.zh.md)
    -  [ ] [资源配置中的6.1个问题](https://github.com/chinanf-boy/systems-Approach-congestion-zh/blob/master/issues.zh.md)
    -  [ ] [6.2排队学科](https://github.com/chinanf-boy/systems-Approach-congestion-zh/blob/master/queuing.zh.md)
    -  [ ] [6.3 TCP拥塞控制](https://github.com/chinanf-boy/systems-Approach-congestion-zh/blob/master/tcpcc.zh.md)
    -  [ ] [6.4拥塞避免机制](https://github.com/chinanf-boy/systems-Approach-congestion-zh/blob/master/avoidance.zh.md)
    -  [ ] [6.5服务质量](https://github.com/chinanf-boy/systems-Approach-congestion-zh/blob/master/qos.zh.md)
    -  [ ] [6.6总结](https://github.com/chinanf-boy/systems-Approach-congestion-zh/blob/master/summary.zh.md)
-  [ ] [第7章: 端到端数据](https://github.com/chinanf-boy/systems-Approach-data-zh/blob/master/problem.zh.md)
    -  [ ] [7.1表示格式](https://github.com/chinanf-boy/systems-Approach-data-zh/blob/master/presentation.zh.md)
    -  [ ] [7.2多媒体数据](https://github.com/chinanf-boy/systems-Approach-data-zh/blob/master/multimedia.zh.md)
    -  [ ] [7.3总结](https://github.com/chinanf-boy/systems-Approach-data-zh/blob/master/summary.zh.md)
-  [ ] [第8章网络安全](https://github.com/chinanf-boy/systems-Approach-security-zh/blob/master/problem.zh.md)
    -  [ ] [8.1个密码构建块](https://github.com/chinanf-boy/systems-Approach-security-zh/blob/master/crypto.zh.md)
    -  [ ] [8.2重点预分配](https://github.com/chinanf-boy/systems-Approach-security-zh/blob/master/key-distro.zh.md)
    -  [ ] [8.3认证协议](https://github.com/chinanf-boy/systems-Approach-security-zh/blob/master/authentication.zh.md)
    -  [ ] [8.4示例系统](https://github.com/chinanf-boy/systems-Approach-security-zh/blob/master/systems.zh.md)
    -  [ ] [8.5总结](https://github.com/chinanf-boy/systems-Approach-security-zh/blob/master/summary.zh.md)
-  [ ] [第9章: 应用](https://github.com/chinanf-boy/systems-Approach-applications-zh/blob/master/problem.zh.md)
    -  [ ] [9.1大传统应用](https://github.com/chinanf-boy/systems-Approach-applications-zh/blob/master/traditional.zh.md)
    -  [ ] [9.2多媒体应用](https://github.com/chinanf-boy/systems-Approach-applications-zh/blob/master/multimedia.zh.md)
    -  [ ] [9.3基础设施应用](https://github.com/chinanf-boy/systems-Approach-applications-zh/blob/master/infrastructure.zh.md)
    -  [ ] [9.4覆盖网络](https://github.com/chinanf-boy/systems-Approach-applications-zh/blob/master/overlays.zh.md)
    -  [ ] [9.5总结](https://github.com/chinanf-boy/systems-Approach-applications-zh/blob/master/summary.zh.md)
