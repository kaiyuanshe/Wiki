# 开源社官网 数据仓库

本仓库通过 [Git 子模块][1]链接到 Hexo 网站的 `source` 文件夹

[![Build Status](https://travis-ci.com/kaiyuanshe/Wiki.svg?branch=master)](https://travis-ci.com/kaiyuanshe/Wiki)

## 写作指南

### 编者入门

![编辑界面](image/Hexo-edit.png)

1.  [注册](https://github.com/join/) 或 [登录](https://github.com/login/)

2.  进入[博文目录](_posts/)

3.  [新建博文][2] 或 [上传图片][3]（此处为**公共图片目录**，博文图片详见下文）

### 博文规范

1.  [博文目录](_post/)下的子目录与 **Category** 一一对应

2.  为了让**博文网址**简洁明了，每篇博文的 `categories` 字段最好只填一个分类，且分类名为一个**首字母大写的英文单词**

3.  **Tag** 只能有文字、不能有符号，否则无法**查询相同标签的文章**

4.  **普通博文**请参考[范文一][4]及其[素材目录][5]

5.  PDF 等可在浏览器直接查看的文档，请参考[范文二][6]

6.  **活动公告**请参考[范文三][7]

## 本机编辑

为了加快图片、视频等**大型二进制文件**的传输速度，本仓库启用了 [Git LFS][8]，请确保在 `git clone` 前装好 LFS 扩展：

```shell
# Windows - Chocolatey
choco install git-lfs

# Mac OS X - HomeBrew
brew install git-lfs
```

[1]: https://git-scm.com/book/zh/v2/Git-%E5%B7%A5%E5%85%B7-%E5%AD%90%E6%A8%A1%E5%9D%97
[2]: https://github.com/kaiyuanshe/Wiki/new/master/_posts/
[3]: https://github.com/kaiyuanshe/Wiki/upload/master/image/
[4]: https://raw.githubusercontent.com/kaiyuanshe/Wiki/master/_posts/International/Codeheat-Open-source-competition.md
[5]: https://github.com/kaiyuanshe/Wiki/tree/master/_posts/International/Codeheat-Open-source-competition/
[6]: https://raw.githubusercontent.com/kaiyuanshe/Wiki/master/_posts/Document/OSI-2015.md
[7]: https://raw.githubusercontent.com/kaiyuanshe/Wiki/master/_posts/Activity/NodeJS-live-2016-BeiJing.md
[8]: https://git-lfs.github.com/
