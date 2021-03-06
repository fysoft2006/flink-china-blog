title: Apache Flink 官方文档翻译开源项目
date: 2016-03-08 13:47:18
tags: 
---

Flink 是一个开源的针对批量数据和流数据的处理引擎，已经发展为 ASF 的顶级项目之一。Flink 的核心是一个提供了数据分发以及并行化计算的流数据处理引擎，并在其上建立了批处理和流处理引擎。

Flink 凭借优异的性能以及在流计算领域的领先，使得其在国外越来越火热，发展速度越来越快。而国内却知之甚少，这也是我们发起官方文档翻译项目的主要原因。希望能够为对 Flink 感兴趣和从事大数据开发人员提供有价值的中文资料，并推动 Flink 在国内的发展。希望能够对大家的工作和学习有所帮助。

本次翻译主要内容是 [Flink 官方文档 1.0 版本](https://ci.apache.org/projects/flink/flink-docs-master/)，也就是即将发布的下一个大版本（刚发现 Flink 官方今天 [发布了 1.0](http://flink.apache.org/news/2016/03/08/release-1.0.0.html)  ）。您可以浏览 [Flink 中文文档](http://doc.flink-china.org/) 查看我们目前的翻译进度。

<!-- more -->

## 参与方式

我们主要以开源协作的方式来组织翻译，您可以浏览我们在 [GitHub 上的项目](https://github.com/flink-china/flink-china-doc)。

### 译者

**如果你想要参与翻译一篇文章，请先在 [issue](https://github.com/flink-china/flink-china-doc/issues) 页面中查看是否已经有人在翻译这篇文档。如果没有，你可以发布一个 issue 或者回复某个模块的 issue，说明你要认领的文档。**

推荐的翻译流程是:

1. 在 issue 页面认领文章。
2. fork [flink-china-doc](https://github.com/flink-china/flink-china-doc) 项目。
3. clone 你 fork 的项目到本地。
4. 找到你认领文章对应的 markdown 文件进行翻译。
5. 将你翻译的结果 push 到你 clone 的仓库中。
6. 通过提交 [Pull Request](https://help.github.com/articles/using-pull-requests/) 的方式提交你的翻译结果。
7. 在 PR 的评论中 @flink-china/review 邀请校对人员进行审核。

翻译的时候，我们建议您直接在原 markdown 文件上进行翻译，也就是直接将原文档中的英文**替换**成你翻译的中文，文中原有的目录、公式、代码、表格等内容都不用动。更多翻译细则请参考 [README](https://github.com/flink-china/flink-china-doc#翻译)。

译文需要至少一位校对人员 +1 后才能被 merge 。

你会发现这种方式翻译方式是很高效的，无需重新排版、无需复制代码、无需编辑公式、无需调整琐碎的站内链接。

### 校对

我们也非常欢迎校对的加入，您可以直接在**本文下方留言您的 GitHub 帐号**，我们会将您添加到校对组中。当译者提交 PR 后，会通过  @flink-china/review 的方式提醒您审核。

校对的方式也非常方便，这主要归功于 GitHub 。如这个 [PR](https://github.com/flink-china/flink-china-doc/pull/6)，可以很方便地对比英文原文和中文译文，并提出修改意见 ：

![](http://ww4.sinaimg.cn/large/81b78497gw1f1pvxekzlhj211g0kktbl.jpg)

我们会尽量保证严格的校对标准，让用户享受到更高质量的中文文档体验。

如果你对开源协作方式感兴趣，如果你对翻译感兴趣，如果你对 Flink、流计算感兴趣，这都是一个非常绝佳的参与机会。我们会在 [致谢页面](http://doc.flink-china.org/about/#thanks) 感谢您的付出。

