---
layout: post
title: 说点新鲜的
image:
  feature: abstract-6.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
comments: true
share: true
---

**缘起**

昨天参加了杭州GDG（Google Developer Group）在杭电举行的交流会，
在活动中再次见识了各路大牛，也稍稍的被刺激了一下，见贤而思齐嘛。

其中，Agassi大神讲了工程师（其实可以认为是互联网行业的程序员）的几个常用工具，
比如Vim、Stackoverflow、git、Trello、Github等，重点是用git和markdown来写博客，这就又勾起了我用jekyll来写博客的
小激情，虽然前几次用jekyll写博客都已失败而告终，但始终无法释怀，人贵在折腾吧。

虽然，题目是*说点新鲜的*，但其实免不了老调重弹。

**正文**

说是到了正文，但这里也没有正经的东西，随便扯扯罢了。

追究起前几次试水jekyll的原因，主要是原来wordpress中近两百篇的博文无法完美的导入jekyll，
尤其是作为中文使用者，各种编码问题更是让人骂×。

算了，经过无数次失败后，也不再挣扎了，还是老老实实把原来的博文手工编辑进来吧。
毕竟原来用富文本编辑器生成的html代码和markdown比起来像shi一样。

说起jekyll的优越性，可能就是比较适合吾等控制欲比较强的人，当有独立博客玩的使用，
我们绝对不愿意把我们的数据放到那些靠谱或不靠谱的博客提供商那里；当有markdown文本
这种放之四海皆准的东西，我们就不愿意被绑死在wordpress这种数据结构固化的系统上。
**我的数据我做主**。

当面临jekyll和其他各种静态博客生成软件的选择时，比较压倒性的一个因素就是：github pages
原生支持jekyll，这样只要把写好的markdown文件扔上去就可以了，没必要自己再手动生成，
而且可以在github的web上在线编辑。

下面说说这次转换过程中遇到的一些问题。

再次尝试了把wp的博文导入，结果依然没有满意的结果，熬了半夜，
也只好无奈的放弃。

ubuntu默认原中ruby太混乱了，默认1.8版本的，但出各种问题，apt-get安装了1.9.3版本，
结果发现只是一个1.9.1的软链接，巨**坑**啊。只好手动编译了ruby最新版，好像已经是2.0以上了。
这再次暴露了一些ubuntu的小问题。

再说说周六的这次分享会，主要是面向学生开发者，简单来说就是让他们开开眼界，包括理念、工具等等。
很多也都是当初我在工作室的时候推动的一些东西，现在离开了，后继无人了。这类活动多参加一点还是好的。

另外在活动中认识了acgtyrant君（[博客](http://acgtyrant.com)），好好向他学习。

换用了zsh，比bash爽得不止一点两点，幸福感大幅度提升，推荐能看到这篇博客的各位试试。

**ps.**

这个博客启用了blog.qlin.net域名，原来的博客内容依然可以通过qlin.net来访问，等手工把博文迁移完了之后也会把根域名指过来的。


-EOF-
