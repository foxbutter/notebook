# 教小白使用 docsify，搭建一个贼简单的所见即所得博客！

[小傅哥 bugstack虫洞栈 _2022-03-04 07:55_](https://mp.weixin.qq.com/s/aK9Z9RkqWMUpcNzUREEx4Q)

### 持续坚持原创输出，点击蓝字关注我吧

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/zTfAIs5rNXgamjlRIWoNaldtybddUlk2e7Gju9LhDdn8cVMOVVRssaaM9U6OIk4q6mDpZsplYsXibEst4RG3B3A/640?wx_fmt=jpeg)

作者：小傅哥  
博客：[https://bugstack.cn](https://mp.weixin.qq.com/s/%3Ca%20target=)">[https://bugstack.cn](https://bugstack.cn/)  

> ❝
> 
> 沉淀、分享、成长，让自己和他人都能有所收获！😜
> 
> ❞

# 目录

  

- 一、前言
- 二、docsify 介绍
	- 1. 目录结构
	- 2. md 说明
- 三、快速搭建博客
	- 1. GitHub Page
	- 2. Gitee Page
- 四、总结
  

## 一、前言

`看我博客挺好，你也想整一个？`

有粉丝伙伴问小傅哥，你那博客：[https://bugstack.cn](https://mp.weixin.qq.com/s/%3Ca%20target=)">[https://bugstack.cn](https://bugstack.cn/) 挺好的我也想整一个，面试写到简历上`还能加分`，也是给自己建设影响力的东西。

不过我没有自己的域名，也没有一些云服务器，还不太会前端的玩意。之后搞的太复杂我又没有时间维护，那有没有简单点的方式，就能搞一个这样博客呢？

---

那当然有哇，你傅哥玩过的博客类型那可多了去了，包括：hexo、vuepress、jekyll、docsify等，这些都能满足你搭建博客的需求。但能满足小白使用的，我强烈推荐 docsify 这货简直是傻白甜都能使用，直接在 GitHub/Gitee 维护一个文档仓库，就可以拥有一个漂亮、简单、好用，易于维护和所见即所得的博客。

**为什么不用 CSDN、掘金、简书？**

当然可以用(`扩大影响力`)，只不过这些都不是原稿存放平台，你的内容输出需要被随心所欲的维护和积累，以及将来需要的时候还可以放置到任何一个其他平台。而你写在 GitHub 仓库，就是最原始的那一份，其他的都是备份传播，这样更有益于你来沉淀、积累和分享。

接下来小傅哥就教你构建这样一个博客，因为我已经帮你准备好了博客模板，所以在这个过程中，你只要跟着步骤，点点点，就部署完事了。**那整吧**，`咱们走起`！

## 二、docsify 介绍

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk26wGJerTPWhjOXFzxO6VicLmxdibFFibPJJ10Le5icABVq18uIibmpLiarSEg/640?wx_fmt=png)

docsify 可以快速帮你生成文档网站。不同于 GitBook、Hexo 的地方是它不会生成静态的 .html 文件，所有转换工作都是在运行时。如果你想要开始使用它，只需要创建一个 index.html 就可以开始编写文档并直接部署在 GitHub Pages。官网：[https://docsify.js.org/#/zh-cn](https://docsify.js.org/#/zh-cn)

### 1. 目录结构

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2UGRibDFrGichlzoQRpTc5dwicsTfHibAzPfXasDsrf62whByg5W2RRIpuQ/640?wx_fmt=png)

- docsify 的目录结构配置非常简单，如果你不需要修改的话，只是 `md` 目录编写文档，在 `_sidebar.md` 配置文章路径即可。
    
- `index.html` 用于配置一些网站的基础信息，包括：网站采集、留言板、地址等。
    
- `_coverpage.md` 用于配置博客首页的介绍信息和网站Logo等
    

### 2. md 说明

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2Vic5AnkQD7R62q9pFRnFmFA1mKYjd1rGfKDTZMsgaq4YLupxcfM33ng/640?wx_fmt=png)

- 所有的文章内容，都是使用 MD 格式进行编写。放心你不会用到太复杂的内容，一个运营小姐姐都可以半天学会。
    
- MD 使用文档：[https://www.runoob.com/markdown/md-tutorial.html](https://www.runoob.com/markdown/md-tutorial.html)
    

## 三、快速搭建博客

这里给大家提供 `GitHub/Gitee` 两种仓库来搭建博客，方便有些小白访问 GitHub 费劲也能用 Gitee 搭建博客。

- 仓库：https://github.com/fuzhengwei/fuzhengwei.github.io
    
- 说明：这是一个 docsify 的博客仓库地址，一些必要的简单配置信息小傅哥已经帮你处理好了，直接使用即可。
    

### 1. GitHub Page

- 优点：规范、部署不限制、自由度高、配置域名不收费
    
- 缺点：国内访问速度慢、仓库不能设置私有
    

#### 1.1 第一步：Fork

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2wKWYYn5bqWiaEQgiaesQNfBCAQjfSfch9lYN1RfoCzcKkyZRygQW44JA/640?wx_fmt=png)

打开 [https://github.com/](https://mp.weixin.qq.com/s/%3Ca%20target=)fuzhengwei/fuzhengwei.github.io">[https://github.com/](https://github.com/)fuzhengwei/fuzhengwei.github.io 点击 fork 到自己的仓库。

#### 1.2 第二步：配置

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2ldQeoFaLSbUo8KKkvEXPuXibVCYKBrAibxXWavV719R2qn5j0eLrO4Dw/640?wx_fmt=png)

- 点击 Setting 进入 General 配置工程名称页面。
    
- **注意**：你必须把 `fuzhengwei.github.io` 修改为你的名称 `xxx.github.io` 这里的 xxx 就是你的GitHub的名称，也是 [https://github.com/](https://github.com/){xxxx} 链接后面的名称，不要修改错了，否则你就失败了。
    

#### 1.3 第三步：开启

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2gzgiasbkicZTMD8TUYGNf4mwCAYhD60tqKiawm3sKLcBr8hAiat9K6CfdQ/640?wx_fmt=png)

- 点击 Setting 进入 Page 页面
    
- 按照上图修改博客资源空间到 `docs` 文件夹下，这个步骤是选择博客空间地址，记得不要配置错了。
    

#### 1.4 第四步：访问

好了，当你在配置后看到已经提醒你 `Your site is published at [https://fuzhengwei.github.io/](https://fuzhengwei.github.io/)` 证明你成功了，你可以访问自己的博客地址了。PS：这里要 `xuewei` 的等一下，因为初始化有一个过程，正在编译稍后就可以访问了。

### 2. Gitee Page

- 优点：访问速度快、博客仓库可以设置私有
    
- 缺点：不能配置自己的域名，需要上传身份信息后才可以使用
    

#### 2.1 第一步：导入

与使用 GitHub 不同，这里是在 Gitee 中导入博客仓库，如下：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2uDPJ4w1vlR1TgADTG2PMEIS1BkNpzAOwLIg9pjMtabM75Xrl5SAxFQ/640?wx_fmt=png)

- 进入导入工程页面：[https://gitee.com/projects/import/url](https://gitee.com/projects/import/url) - 也可以从 gitee 右上角的 `+` 号进入。
    
- 复制博客模板：[https://github.com/](https://mp.weixin.qq.com/s/%3Ca%20target=)fuzhengwei/fuzhengwei.github.io">[https://github.com/](https://github.com/)fuzhengwei/fuzhengwei.github.io 粘贴到 `Git 仓库 URL` 即可。
    
- 修改`仓库名称`、`路径`，为你的 gitee 账号名称，我这里的名称为 `yamiedei`，你复制自己的就可以了。
    

#### 2.2 第二步：配置

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2X4u5qh4lAw1E79lqdn2xkMoCz3htcNEja1iarQbcjkICG24j8exhg6w/640?wx_fmt=png)

- 从 `服务` 的 `Gitee Pages` 进入即可进入配置博客页面。
    
- 不过由于大家基本都是初次使用 Gitee Pages 它会要求你上传认证信息，一天内审核完成。
    

#### 2.3 第三步：认证

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2wYhdM3KSJGysEM6AmyzZyYOIVpCztKyObdSZdoArEge6Whc1sR7iaFg/640?wx_fmt=png)

- 如果你到了这个页面，可以提交资料后，第二天再继续了。
    

#### 2.4 第四步：开启

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/zTfAIs5rNXgamjlRIWoNaldtybddUlk2rHIlic1r8W1KqCPmR2opaWbPDU5yFPrtqOrt4TZw9liaGFxSnticYQ8pQ/640?wx_fmt=png)

- 如果以上步骤都完事了，接下来你就可以开启自己的博客了，同样会给你一个博客地址，每次上传新的文章点击更新即可。
    

## 四、总结

`程序员，为什么要写博客？`

我，`软件工程`毕业？上学时觉得，毕了业就是开发工程师，但没想到工作些年还成了 PPT 工程师。

为啥呢？因为写代码只是作为一个程序员的最基本能力，如果还想继续在这条路上往前走，就需要有；提炼逻辑能力，制定标准手段、落地执行方案，而这一步步的推进都需要，就是将你的思考转换为可以看得见的内容，无论它是PPT、拓扑图、流程图还是思维导图，总之你需要一个合适的工具来表述你的想法，与沟通者最低成本完成消息传递和确认执行。

那么对于程序员来说，这个代码之外的能力成长，更好的方式则是`编写博客`、`记录分享`、`积累沉淀`，通过这样一个过程来不断的完善自己在内容表述上的能力，以及拓宽和拉伸自己的技术栈体系。

好嘞，现在你也拥有了一个可以像维护代码仓库一样的文档博客，并且随着你的学习过程，不断的完善、补充、沉淀，慢慢你终将会成为一名优秀的码农大佬。加油！

**如果你已经搭建好了，可以在评论区留下你的博客地址哦！**