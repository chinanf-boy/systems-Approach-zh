
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

-   [GITBook工具链](https://toolchain.gitbook.com/setup.html)
-   [JS包管理器](https://www.npmjs.com/get-npm)

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

如果你想贡献任何补丁或新材料,你需要签署一个[捐助者许可协议 (CLA) ](https://github.com/SystemsApproach/book/blob/master/CLA.md). 当你第一次提出拉请求时,会提示你在CLA上签名. 

CLA非常简单: 它确立了 (a) 您有权利贡献您正在贡献的内容,以及 (b) 您所贡献的内容对于相同条件下的其他所有人都是可用的[抄送](https://creativecommons.org/licenses/by/4.0)作为现有内容的术语. CLA有一点不同寻常,因为它明确地宣布了Elsevier的权利 (这和每个人的权利一样) ,但这确实表明他们打算继续根据教材出版教科书. 

你也应该熟悉自己. [投稿指南](https://github.com/SystemsApproach/book/blob/master/CONTRIBUTING.md). 作为第一步,我们建议您检查,看看是否有新的文本,你想提交通过我们`MarkDownLint`测试. 要做到这一点,运行

```shell
cd ~/systemsapproach
make lint
```

如果你想做出贡献并寻找需要注意的东西,请参阅当前[项目委员会](https://github.com/orgs/SystemsApproach/projects/). 我们还想扩展主题集/章节,超出从第五版继承的初始集,所以如果你有想法,我们很想听听你的. 发送电子邮件到`discuss@systemsapproach.org`或者更好,[加入论坛](https://groups.google.com/a/systemsapproach.org/forum/#!forum/discuss).

最后,正如这是一个持续的努力,我们将尝试记录和跟踪我们的. [进步](https://github.com/SystemsApproach/book/blob/master/status.md). 现在,把这看作是穷人的发行说明. 

## 加入我们

我们希望你能从中得到价值*计算机网络: 一种系统方法*多年来,我们热切希望你能加入我们的新事业. 

Larry Peterson与Bruce Davie\
2018年8月
