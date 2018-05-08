---
title: 网站
date: 2018-01-18 15:19:07
tags: hexo
categories: hexo
---
#### 日常操作

* 依次执行git add .、git commit -m “…”、git push origin hexo指令将改动推送到GitHub（此时当前分支应为hexo）；
* 然后才执行hexo generate -d发布网站到master分支上。

##### 本地资料丢失

**当重装电脑之后，或者想在其他电脑上修改博客，可以使用下列步骤**

* 使用git clone git@github.com:CrazyMilk/CrazyMilk.github.io.git拷贝仓库（默认分支为hexo）；
* 在本地新拷贝的CrazyMilk.github.io文件夹下通过Git bash依次执行下列指令：npm install hexo、npm install、npm install、hexo-deployer-git (记得，不需要hexo init这条指令)

