---
title: 搭建HEXO采坑记
date: 2018-07-23 16:31:40
copyright: true
---
<blockquote class="blockquote-center">优秀的人，不是不合群，而是他们合群的人里面没有你</blockquote>

安装依赖时可能会报几个依赖包加载失败的错误
```
$ ERROR Plugin load failed: hexo-renderer-marked ......

```
解决办法
```
$ npm install
```

当项目提到github仓库时如果没有添加CNAME文件，打开我们所映射的网址github会提示报错
* 需要在source文件夹下新建CNAME文件，写入映射域名保存重新提交；
