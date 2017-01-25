---
title: latex
date: 2017-01-25 20:23:46
tags:
---

久闻latex大名，但是一直没有找到好用的latex写作环境，所以用的比较少。不过现在现在有了atom之后，尝试了一下，感觉还是挺舒适的。

## 环境配置
1. 安装atom
2. 最新版的atom应该已经自动配置好了环境变量，所以win+r cmd 打开命令行，输入以下命令，安装需要的插件
```
apm install latex
apm install pdf-view
```
如果你和我一样是vim党，可以

3. latex插件要求预装latex环境，可以选择tex live或MiKTeX。我选择安装tex live，在这里[下载](https://www.tug.org/texlive/)。 建议离线下载，大小2个多g。下载和安装都需要比较多的时间。

## 测试
1. 在http://www.latextemplates.com/ 下载一个模板。
2. 用atom打开tex后缀的文件，点击Packages->latex->Build。可以看见目录中已经生成了pdf文件，可以直接在atom中预览，因为已经装了插件。另外还有一堆中间文件。
