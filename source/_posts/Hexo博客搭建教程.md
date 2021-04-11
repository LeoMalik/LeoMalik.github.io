---
title: Hexo博客搭建教程
tags:
  - hexo
categories:
  - hexo
date: 2021-04-11 00:19:51
index_img: /img/wlop/wlop (1).jpg
banner_img: /img/wlop/wlop (1).jpg
comments: true
---

## 说在前面

先看文档，先看文档，先看文档📖📖📖

99%的答案在文档里都能找到！

<!-- more -->

## 新建hexo博客

应该没有更详细的了🤯：https://zhuanlan.zhihu.com/p/35668237

## 设置喜欢的主题

https://hexo.fluid-dev.com/docs/start/#%E6%90%AD%E5%BB%BA-hexo-%E5%8D%9A%E5%AE%A2

效果图如下，还是狠好看滴🥳：

![](https://gitee.com/leo_clip/imgbed/raw/master/20210411003134.png)

## 个性化博客

文档链接：https://hexo.fluid-dev.com/docs

推荐插件：https://hexo.fluid-dev.com/docs/plugin/

这里我主要做了以下几个变动:

- 开启网站统计，需要配合[leancloud](https://console.leancloud.cn/apps)服用💊（创建个app，记住appid和appkey就行了）
- 修改网页背景和标题（请看文档）
- 修改默认模版： ``vim scaffolds/post.md``
- 提交谷歌和百度收录：https://zhuanlan.zhihu.com/p/100922816
- 增加评论模块（这里用的是valine）
  - 评论邮件提醒（注意⚠️这里要用国际版的leancloud，否则域名要备案）：
    - https://github.com/DesertsP/Valine-Admin
    - https://lanlan2017.github.io/blog/de4f7be8/
- 增加rss订阅
- ...其他根据个人喜好自行修改

## 撰写文章

我用的是typora+picgo+markdown来进行配文，参考：https://zhuanlan.zhihu.com/p/102594554

markdown：https://www.runoob.com/markdown/md-tutorial.html

## 发布文章

生成文章：https://zhuanlan.zhihu.com/p/102594554

生成文章后自动打开编辑器：https://www.wildptr.cn/posts/22932.html

- 这个功能还是比较重要的，不然文章多了还要一个个去文件夹里找，很不方便😓

## 自动备份&一键发布

https://quareia.github.io/blog/6efb1d64/

参考流程后自己写了个alias（懒😴:

![image-20210411010634569](https://gitee.com/leo_clip/imgbed/raw/master/image-20210411010634569.png)

## 最终效果

https://leomalik.github.io/

为了方便，也可以到https://github.com/LeoMalik/LeoMalik.github.io 的source分支下复制我的博客源码直接使用😇









