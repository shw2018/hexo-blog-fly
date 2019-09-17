---
title: 博客开源
date: 2019-08-27 11:41:03
author: 洪卫
img: 
coverImg: /medias/banner/0.jpg
top: true
cover: true
toc: true
mathjax: false
summary: 
  倒腾了一两周总算把个人博客网站完善了，目前这个版本使用应该是够了，当然还有一些优化项和功能增加后续在慢慢更新，为了回馈开源，今天准备把我自己修改完善的`blog`网站源代码开源。这不是生成后的网页文件，是您可以直接使用的源码，您只需要把博客相关信息换成您自己的就可以部署了。
tags:
  - Hexo
  - Github
  - 博客
categories:
  - 软件安装与配置
password:
---

# 效果演示
![演示Demo](https://raw.githubusercontent.com/shw2018/cdn/master/blog_files/img/Blog-Open-Source/blog-demo1.gif)

# 简短介绍

倒腾了一两周总算把个人博客网站完善了，目前这个版本使用应该是够了，当然还有一些优化项和功能增加后续在慢慢更新，为了回馈开源，今天准备把我自己修改完善的`blog`网站源代码开源。这不是生成后的网页文件，是您可以直接使用的源码，您只需要把博客相关信息换成您自己的就可以部署了，对于新手或者不懂编程的小伙伴来说，简直是福音，极大简化了您构建博客的工作量和复杂度，每个人都可以下载并修改成自己喜欢样式！如果你有修改想法，欢迎PR！最后，我们还是给这个开源小项目取个名字吧，就叫[hexo-blog-fly](https://github.com/shw2018/hexo-blog-fly.git)吧，怎么样？<<<<<[源代码下载](https://github.com/shw2018/hexo-blog-fly)>>>>>

本博客基于`Hexo`框架搭建，用到[hexo-theme-matery](https://github.com/shw2018/hexo-theme-matery)主题, 并在此基础之上做了很多修改，修复了一些bug，增加了一些新的特性和功能，博客地址：[https://shw2018.github.io](https://shw2018.github.io/)，博客演示：[sunhwee.com](https://sunhwee.com)。

---

## 特性

**原主题特性**:

- 简单漂亮，文章内容美观易读
- [Material Design](https://material.io/) 设计
- 响应式设计，博客在桌面端、平板、手机等设备上均能很好的展现
- 首页轮播文章及每天动态切换 `Banner` 图片
- 瀑布流式的博客文章列表（文章无特色图片时会有 `24` 张漂亮的图片代替）
- 时间轴式的归档页
- **词云**的标签页和**雷达图**的分类页
- 丰富的关于我页面（包括关于我、文章统计图、我的项目、我的技能、相册等）
- 可自定义的数据的友情链接页面
- 支持文章置顶和文章打赏
- 支持 `MathJax`
- `TOC` 目录
- 可设置复制文章内容时追加版权信息
- 可设置阅读文章时做密码验证
- [Gitalk](https://gitalk.github.io/)、[Gitment](https://imsun.github.io/gitment/)、[Valine](https://valine.js.org/) 和 [Disqus](https://disqus.com/) 评论模块（推荐使用 `Gitalk`）
- 集成了[不蒜子统计](http://busuanzi.ibruce.info/)、谷歌分析（`Google Analytics`）和文章字数统计等功能
- 支持在首页的音乐播放和视频播放功能

 **增加的工作或特性(未打钩的是已做但还没更新到源码的)**:

- 修改了原主题的一些很多`bug`   2019.08.05
- 加入图片懒加载功能，在根目录配置文件开启和关闭    2019.08.09
- 增加`留言板`功能          2019.08.05
- 在关于板块,加入`简历`功能页   2019.08.05
- 增加视听[视觉听觉影音]板块       2019.08.10
- 支持`emoji`表情，用`markdown emoji`语法书写直接生成对应的能**跳跃**的表情。  2019.08.10
- 增加网站运行时间显示  2019.08.10
- 增加`动漫模型`     2019.08.10
- 整体替换Banner图片和文章特色图片   2019.08.10
- 增加分类`相册`功能         2019.08.29
- 去掉标签页,将其合并至`分类`页中                2019.09.01
- 修改了一些控件的参数   2019.09.01
- 修改部分样式,比如: 文章卡片,固定高度,使其不至于因为文章摘要的长短不同导致卡片大小不一使页面布局很不美观,类似的还有友链卡片,优化了页面内容布局,视觉更整齐美观          2019.09.01
- 解决首页文章列表卡片上方 `border-radius`圆角失效的bug  2019.09.01
- 添加页面樱花飘落动效            2019.09.09
- 添加鼠标点击烟花爆炸动效   2019.09.09
- 加入天气接口控件   2019.09.09
- 加入鼠标点击文字特效   2019.09.10
- 添加页面雪花飘落动效            2019.09.10
-  添加在线聊天插件            2019.09.12
-  持续更新...

---

**简单使用方法：**
1. `star` 本项目
2. 安装[Git](https://git-scm.com/downloads), 安装[nodeJS](https://nodejs.org/en/)
3. 你可以直接`fork`一份源码到你的仓库，`clone`到本地
4. 在本地博客仓库运行`npm i`命令安装依赖包
5. 修改配置信息，改成自己的信息
6. 运行命令`hexo  clean`（清除生成文件），`hexo g`（生成网页）， `hexo  s`（本地预览），`hexo d`（部署）


>**更多详情教程，强烈推荐看我写的：[Hexo+Github博客搭建完全教程](https://sunhwee.com/posts/6e8839eb.html)**

>**最后，如果项目和教程对你有所帮助或者你看见了还算比较喜欢，欢迎给我`star`，谢谢您！**

**持续更新中...，如果遇到问题欢迎联系我，在文章最后评论区【留言和讨论】，当然，欢迎点击文章最后的打赏按键，请博主一杯冰阔乐，笑～**
<escape>
<table>
  <tr>
    <td><img width="100" src="https://sunhwee.com/medias/reward/alipay.bmp" ></td>    <td><img width="100" src="https://sunhwee.com/medias/reward/wechat.bmp" ></td>    <td><img width="100" src="https://sunhwee.com/medias/reward/zan.png" ></td>   
  </tr>
</table>
</escape>