---
description: 怎么走进漏洞挖掘的大门，听听大牛怎么说
---

# 小白入门

以下内容来自「[CanMeng'Blog - 一个WEB安全渗透的技术爱好者](http://canmengblog.lofter.com/)」，我看了之后深受启发，也由此开启了正确的漏洞挖掘之路，具体内容如下：

他将漏洞挖掘分两个部分进行讲解：一，漏洞挖掘类型总结，二、个人提高漏洞挖掘能力的方法。

## 漏洞类型总结

除常见的web类型的漏洞之外，还要在你的清单中更新如下漏洞类型。

* 常见漏洞类型：
  * 暴力破解漏洞，sql注入漏洞，命令执行漏洞，xss漏洞（跨站脚本），csrf漏洞（跨站请求伪造），xxe漏洞，文件上传漏洞，文件包含漏洞，各大cms公开漏洞
* 更新漏洞类型：
  * 逻辑漏洞，ssrf漏洞，信息泄露，js文件可能存在的未授权访问，组合漏洞

更新漏洞的介绍：

* 逻辑漏洞：由于开发者在开发过程中，由于代码逻辑不严，而造成的一系列可以被攻击者加以恶意利用的漏洞。包括验证码爆破，支付漏洞，注册/忘记密码处理逻辑漏洞，越权漏洞等；
* 信息泄露：信息泄露漏洞顾名思义就是信息泄露，包括源码泄露，用户信息泄露，员工信息泄露等等；
* 组合漏洞：低危漏洞组合成为高危漏洞，例如xss漏洞和csrf漏洞的混合提交。
  * key师傅给我说：「挖到低危不要着急提交，存起来，万一某一天碰见另一个漏洞，组合一下，就可以一发入魂了。」

## 漏洞挖掘能力提升

* 养成好的习惯：细心  耐心  会看  会记  懂收集  勤动手  爱学习
* 具体介绍：
  * 细心：不放过数据包中的任何一个参数，不放过网站的任意一个点，**心细则挖天下**
  * 耐心：细心的好cp，没有耐心的漏洞挖掘人员是不合格的好士兵，嘿嘿：-）
  * 会看，会记：

    * 多看漏洞详情，多看技术文章；
    * 光看不行还要记，要让你看的东西真正的成为你的东西；

    **重点：**

    * 看漏洞详情，把漏洞出现的位置以及使用的技巧记下来，成为属于自己的漏洞挖掘手册，这也是我最近在做的一个事情。还有一些好的文章，好的技巧，或许你一时半会也用不到，但是你要学会记，总有用到的一天。

  * 懂收集：

            漏洞挖掘说白了就是fuzz的过程，而fuzz最关键的就是有一本高效的字典。我们要学会收集字典，已经公开的字典有fuzzdb，是一个非常好的fuzz字典合集，当我们在收集他人字典的同时我们也要自己收集字典，曾经看到一个大佬，搜集了github大量的开发项目的路径，然后组成字典。我也不要求小白可以写程序然后自动收集字典，但是，我们在平时的漏洞挖掘过程中，遇到的一些东西还是要多多的去收集一下，逐步慢慢的形成自己的一本专用字典，绝对可以提高你的漏洞挖掘效率。当你有一本自己收集的字典时，相信你也成为一名大佬了。

  * 勤动手

            当你看了大量漏洞，记了大量笔记，这个时候，我相信你最需要的，就是实战，实战是可以把所学所看**融会贯通**的最快方法，没有之一，只有实战可以锻炼自己的挖洞能力和效率。看到新的漏洞多去搭建环境复现，这也是对能力的一种提升。

  * 爱学习

            学习，学无止境，知识面有多广，决定了你可以挖多少漏洞，多学习，至于学什么呢，学js，学[代码审计](http://bbs.ichunqiu.com/forum-59-1.html)，学开发，学json，等等等等，有的时候真的感觉，你要成为一个开发人员，了解详细的信息传输和交换原理，才可以挖到更加深入的漏洞。如果有一天你感觉挖不到漏洞了，不如放下手头的一切去学习吧，小伙子。

## 后记

以上内容来自「[CanMeng'Blog - 一个WEB安全渗透的技术爱好者](http://canmengblog.lofter.com/)」，如果你觉得对你有用，那么请带着你满满的激情开启你在漏洞挖掘领域的新征程吧，加油少年！其实漏洞挖掘没有你想象的那么难，只要有耐心，有恒心，肯创新，肯钻研，那么你迟早在这条路上能够有属于自己的一席之地！
