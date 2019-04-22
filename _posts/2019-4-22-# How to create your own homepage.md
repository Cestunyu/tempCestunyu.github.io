# How to create your own homepage 



[TOC]

## Learning Curve for myself:

13 min Checking out for material 
12 min Collecting the material and organize my priorities
* Learn the mechanism of Github and use it to share resources 
*  Learn how to upload your essay and report
*  How to change your

CSS 

* Intro: https://keysaim.github.io/post/blog/2017-08-15-how-to-setup-your-github-io-blog/

* https://zhuanlan.zhihu.com/p/28321740

* More Specific one:https://blog.csdn.net/pipisorry/article/details/51707366

* http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html

* Main: https://pages.github.com



Custom Domain:

* https://help.github.com/en/articles/using-a-custom-domain-with-github-pages
* 



Themes:

* https://www.zhihu.com/question/20376047
* https://cargo.site/In-Use/No-Blinking



More Information:

* http://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html





Get used to github

* 



How to use HTML:

* https://www.jianshu.com/p/5ef69bab18d2





Tree

* The use of Github;(How to use command to control Github)

## Abstract 

* Set up your own GitHub.io repo/
* Choose a Jekyll theme.
* Starti writing! Enjoy!



## Recipe for creating your own GitHub.io 

### Part 1
登陆你的账户后，你可以[创建一个新的repo](https://github.com/new)。**请务必注意该repo的名字，必须保持格式<username>.github.io，其中<username>替换成你的github账户名**，这里假定创建的repo为`tobiasalin.github.io`

![image-20190420150821693](/Users/yuun/Library/Application Support/typora-user-images/image-20190420150821693.png)

![image-20190420150902860](https://ws1.sinaimg.cn/large/006tNc79gy1g2947ny8qcj314805w75c.jpg)



随后跳转到该库界面,由于我是搭建好的，所以会有项目文件，然后选择Settings

![image-20190420153654886](https://ws2.sinaimg.cn/large/006tNc79gy1g2950nvhgij30zj0u0ted.jpg)

Thus we have finished the first part of it.![image-20190420154433749](/Users/yuun/Library/Application Support/typora-user-images/image-20190420154433749.png)



### Part 2 





## Jekyll

### What is the purpose/function of jekyll?

* Using markdown to create page instead of html

### Shortage 

* Not flexible/extensional enough for some hardcore blogging.



## Binding your own domain name

另外，有一个功能很重要，就是绑定自己的域名。想想如果有天 github 网站被和谐了，那怎么办？如果一开始就是用自己的域名，那就简单了，换一台服务器就好了。

绑定域名的具体的操作步骤在[这里](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/) 。我的 gitbeijing.com 这个域名是在 godaddy.com 上买的。 到 godaddy.com 上，添加 A Record 指向 185.199.111.153 ，注意这个 IP 可能会在未来发生变化，具体值请参考[官方文档](https://help.github.com/en/articles/troubleshooting-custom-domains#https-errors)。并且添加一个 CNAME ，以便让 www.gitbeijing.com 可以重定向到 gitbeijing.com 。

要到 [gitbeijing/gitbeijing.github.io](https://github.com/gitbeijing/gitbeijing.github.io)项目的 settings 页面，添加域名，并强制使用 HTTPS 。

点按钮确认后，github 会在仓库中自动创建 CNAME 文件，里面的内容为

```
gitbeijing.com
```

这样操作结束，可能还要稍微等几个小时给 DNS 扩散以及 HTTPS 的证书的颁发。然后访问 <gitbeijing.com> 或者访问 <www.gitbeijing.com> 都可以跳转到 [https://gitbeijing.com](https://gitbeijing.com/) ，并打开网站了，效果完美。





## Reference

https://gitbeijing.com/pages.html#jekyll

