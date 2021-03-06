---
title: 独立博主个人站长经验分享
author: zhaoolee
tag: 博客
---


# Think Blog
这是一篇长文, 目标是忽悠更多的人来写有趣的博客.

本文提到的内容，可以到[https://bbs.v2fy.com/c/think-blog/](https://bbs.v2fy.com/c/think-blog/) 发帖提问, 作者会第一时间回应, 为了让更多人看到本文, [Github也会同步更新: https://github.com/zhaoolee/think-blog](https://github.com/zhaoolee/think-blog)

## 写博客有什么好处?

写博客可以放慢时间, 一周写七篇博客, 和混吃等死过一周, 肯定是混吃等死过得快.

写博客能抵御思维僵化,  写博客的过程, 需要大脑进行长线地思考, 万千思维聚沙成塔, 深入思考的大脑, 比常年刷抖音嗑CP的大脑更灵活.

写博客让人不沉溺负面情绪, 写作作为一种情绪的表达, 可以为不良情绪释压

写博客可以让人不断学习, 不断进步；问渠那得清如许？为有源头活水来，写博客是输出，有输出就要有输入，输入新知识，终身学习，有助于降低老年痴呆的风险

写博客可以让人思维更缜密，吵架赢的几率更高；文章是需要逻辑的，写东西的人，为论点列出123点论据是基操，双方吵架，如果实力接近，往往讲的更快的人占上风，面对一个嘴巴比脑子还要快的对手，如果能列出3条论据，可以用逻辑轻松KO对手

写博客可以带来各种经济收益；新东方某年年会，有句歌词**干活的干不过写PPT的**，好的PPT，往往是文案直击人心，做了同样多的工作，年终总结写的好，肯定会多一些经济收益， 博客写得再好一些，还可以通过流量收[Google Adsense](https://www.google.com/adsense/start/)广告费。 

## 推荐写博客的工具

强烈推荐使用[Markdown](https://www.runoob.com/markdown/md-tutorial.html)进行创作, Markdown是纯文本, SEO良好, 容易被搜索引擎索引, 也可以简化排版, 节省时间

如果你喜欢使用电脑码字, 我推荐使用[Typora](https://typora.io/), 码字体验很棒, 跨平台,  是Windows系统最舒服的码字工具， 如果你是macOS系统, 且追求极致的码字体验, 且不差钱, 可以试试付费的[Ulysses](https://ulysses.app/)

如果你喜欢使用手机码字, [锤子便签](https://yun.smartisan.com/#/notes)是不错的选择, 但锤子便签Markdown模式下, 支持的Markdown语法不完全, 只适合纯码字而不插入图片, 否则导出markdown到其它平台会非常麻烦.

如果你懒得折腾, 可以直接选择在[简书](https://jianshu.com)码字, 虽然简书里面的文章水的一比, 但编辑器还是很好用的, 支持Markdown, 且支持PC端和手机端同步.

如果你愿意折腾, 我推荐自建[Discourse](https://github.com/discourse/discourse) 站, 在帖子里面码字, 支持完整的Markdown, 无需下载手机App, 打开浏览器, 移动端和PC端可同步码字, 且自动存草稿, 体验极佳.


## 选题哪里来？

长期选题可以找自己擅长的领域，比如摄影，Windows，Chrome，编程，Linux实用入门教程，长期健身经验分享，球类运动技巧，运动装备选择，好物推荐...  长期选题可以做成连载, 用Github仓库进行管理, 一个选题一个仓库, 有新内容了, 就更新一个版本, 文章托管到Github仓库的README.md, 搜索引擎会自动为你带来持续优质的SEO流量.

短期选题可以通过[今日热榜](tohub.today) 获取最新全网热点信息

## 域名和服务器选择

独立博客可以不买服务器, 但一定要买一个域名, 如果你想备案的话, [买.com域名](https://wanwang.aliyun.com/) 是坑最少的, 一些小众域名很便宜很酷, 但不能在中国备案, 不备案的话, 百度统计, 公众号平台, 微信小程序api接入都无法使用。

独立博客需要服务器存放网页, [Github Pages](https://pages.github.com/)完全免费, 无限流量, 无限空间,全球CDN, 支持绑定自己的域名, 但是由于中国网络环境特殊, github pages的页面访问速度很慢, 而且图片大概率无法访问.

如果要提升博客访问速度, 就要买国内的主机, 比如阿里云, 华为云, 腾讯云, 推荐买全功能的虚拟主机[VPS产品](https://common-buy.aliyun.com/?commodityCode=swas&regionId=cn-hongkong), 拥有完整的权限, 可以自行安装各种数据库服务, Nginx网关, WordPress建站程序, Discourse论坛程序, 网易云解锁灰色歌单服务程序, PM2脚本守护服务, frp内网穿透服务, 自建图床服务... 可玩性和自由度极高。


## 关于个人网站备案

使用国内的主机, 要走备案流程, 备案由服务器厂商提供服务, 一般是买一年的服务器, 厂商为你提供一次备案服务, 备案大致两周可搞定, 备案期间除了 80 和 443 端口访问受限, 其它功能不受影响.

我在阿里云和腾讯云都备案过, 阿里云流程更顺一些.

域名备案是绑定主机厂商的, 比如域名 v2fy.com 解析到腾讯与服务器, 并完成了备案, 如果要迁移到阿里云, 需要重新备案, 有一说一, 这个规则很坑, 如果你不想反复走备案流程, 能不换云服务厂商, 就不要换.


## 如何建立网站?

建站程序分为两大类, 静态建站程序和动态建站程序

**静态网站程序**有[Hexo](https://hexo.io/zh-cn/) , [Hugo](https://gohugo.io/), [jekyll](https://jekyllrb.com/) 等, 原理是把markdown转换为html页面, 另外还有 docsify 这种完全前端渲染的静态建站程序，好处是省去了渲染步骤，代价是牺牲了一些SEO分数。

**动态建站程序**推荐[WordPress](https://wordpress.org/download/)，免费且插件丰富，有近20年的技术积累，全球42% 的网站基于WordPress搭建, 插件丰富, 对网站的方方面面都有现成的解决方案, 选择了WordPress, 可以让你不写一行代码, 构建稳定可靠的博客网站.

如果你想建立社区, 推荐Discourse建站程序，Discourse号称是面向未来10年的开源社区 , 开源免费, PC和移动端体验都很棒, 支持草稿自动保存, 如果你在PC浏览器编辑器编辑, 然后打开手机可以接着写, 重回PC的时候, PC浏览器编辑器会自动弹窗询问你, 是不是需要重载页面, 拉取最新内容.


## 如何推广自己的博客?

刚开始的小网站一般是没什么流量的, 我们可以主动提交给[Google console](https://search.google.com/search-console), [百度搜索平台](https://ziyuan.baidu.com/linksubmit/index), [必应网站管理员](https://www.bing.com/webmasters/about), 这样主流搜索引擎,就会收录我们的网站了


利用内容平台引流, 微信公众号每篇文章底部的阅读原文, Github个人页自定义放个人网站的链接, 简书文章底部手动留一个阅读原文, 类似的还有知乎, 哔哩哔哩都可以在文章底部留一个自己网站的原文链接, 这些都是极好的免费宣传引流方式, 细水长流, 持续产出优质内容, 内容创造之神也会多看你两眼...
