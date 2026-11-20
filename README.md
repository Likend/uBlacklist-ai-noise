# uBlacklist-ai-noise

这是一个反 AI 内容牧场专用的 uBlacklist 规则订阅地址。

本项目思路来源于[这篇文章](https://www.zhuqiy.com/posts/content-farm-exposed/)。

## 什么是 AI 内容牧场？

一些垃圾网站通过 SEO 优化、堆砌关键词的方式，让自己的内容在搜索引擎的排名靠前。过去，这类网站的内容依靠大量的人工编写，或者直接从其他网站搬运。生成式 AI 发达之后，一些新网站开始使用 AI 大量生成垃圾内容来霸占搜索引擎，其领域广度、内容数量是前所未有的。单个网站一天生成的内容就达到成百上千条，远远多于一个高质量内容博主几年来产生的文本。

这些 AI 内容通常都是一些小模型生成的，幻觉严重。同时内容必然没有实操验证，容易误导人，丝毫没有一点价值。本规则集优先封禁 这些 AI 内容牧场，目前已经针对 CSDN 和 gitcode 的 AI 内容、云原生实践（www.oryoy.com）以及其所有友情链接（全是一大堆界面相似的矩阵站）等网站做了屏蔽。

## 使用

1. 在浏览器安装 uBlacklist 扩展；
2. 打开扩展设置。将下面链接添加到设置中的“订阅黑名单列表”：

   [https://github.com/Likend/uBlacklist-ai-noise/raw/refs/heads/main/uBlacklist.txt](https://github.com/Likend/uBlacklist-ai-noise/raw/refs/heads/main/uBlacklist.txt')

3. 远离 AI 噪声的，享受清静的搜索吧！

## 贡献

如果您发现了其他的 AI 内容牧场网站，可以以任何方式联系我，包括 github issue。
