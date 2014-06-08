title: Django
category: page
slug: django
sort-order: 022
choice1url: /cascading-style-sheets.html
choice1icon: fa-css3 fa-inverse
choice1text: 用户界面非常糟糕，我怎样美化我的web应用呢？
choice2url: /api-integration.html
choice2icon: fa-link fa-inverse
choice2text: 我想将外部的API整合进我的Django项目。
choice3url: /deployment.html
choice3icon: fa-share fa-inverse
choice3text: 我已经用Flask写好一个web应用了，怎么部署呢？
choice4url: /source-control.html
choice4icon: fa-code-fork fa-inverse
choice4text: 我如何控制、管理我的源代码不使其丢失呢？


# Django
[Django](http://www.djangoproject.com/)是一个以“内置电池”为设计哲学的被广泛使用的Python web应用框架。“内置电池”的原则即是构建web应用的常见功能应该包含在框架之内，而不是依赖单独的外部库。


<img src="theme/img/django-logo-positive.png" width="100%" alt="Official Django logo. Trademark Django Software Foundation." class="technical-diagram" />


举个例子，
[用户认证](https://docs.djangoproject.com/en/dev/topics/auth/)、
[URL路由](https://docs.djangoproject.com/en/dev/topics/http/urls/)、
[模版系统](https://docs.djangoproject.com/en/dev/topics/templates/)、
[对象关系映射ORM](https://docs.djangoproject.com/en/dev/topics/db/)和
[数据库迁移](https://docs.djangoproject.com/en/dev/topics/migrations/)
(1.7版本引进)都包含在[Django框架](https://pypi.python.org/pypi/Django/1.6.2)中。试着比较一下自带用户认证功能的Django框架和依赖外部库如 [Flask-Login](https://flask-login.readthedocs.org/en/latest/) 实现的Flask框架。

在框架本身的构建中，“内置电池”和“可扩展”这两种哲学显然大相径庭，不过这两种内在哲学并没有哪个好哪个不好。

## 为什么Django是个不错的选择？
Django项目的稳定、性能、社区自其诞生的十年来取得了极大的成长。不管是书中还是在网上很容易就能获取到详尽的教程和最佳实践（best practices），并且随着新版本的释出，很多有意义的新功能如[数据库迁移](https://docs.djangoproject.com/en/dev/topics/migrations/)还在继续加入到框架中去。

我强烈推荐Python web开发新手们以Django作为起点，因为在软件开发的过程中官方提供的文档和教程都是一些精品资源。另外许多城市都有专门的Django团体，诸如[Django District](http://www.meetup.com/django-district/),
[Django Boston](http://www.meetup.com/djangoboston/) 和 
[San Francisco Django](http://www.meetup.com/The-San-Francisco-Django-Meetup-Group/)， 
许多新手开发者在遇到问题时可以在那里得到帮助。［译者注：中文社区］

另外有一个争论点是：有人认为[通过Django来学习Python是个坏主意](http://www.jeffknupp.com/blog/2012/12/11/learning-python-via-django-considered-harmful/)。不过，在你投入到web开发之前你已经花时间学习了Python的语法、语义的话，这些批评的声音就大可不以为意了。


## Django资源
* [Tango with Django](http://www.tangowithdjango.com/book/) are a extensive 
  free introductions to using the most popular Python web framework. Several
  current developers said this book really helped them get over the initial
  framework learning curve.

* [2 Scoops of Django](http://twoscoopspress.com/products/two-scoops-of-django-1-6) 
  by Daniel Greenfield and Audrey Roy is well worth the price of admission if
  you're serious about learning how to correctly develop Django websites.

* [Effective Django](http://effectivedjango.com/) is another free introduction
  to the web framework.

* The [Django subreddit](http://www.reddit.com/r/django) often has links to
  the latest resources for learning Django.

* Lincoln Loop wrote a 
  [Django Best Practices guide](http://lincolnloop.com/django-best-practices/)
  for the community.

* Steve Losh wrote an incredibly detailed [Django Advice guide](http://stevelosh.com/blog/2011/06/django-advice/).

* [Lightweight Django](http://programming.oreilly.com/2014/04/simplifying-django.html)
  has several nice examples for breaking Django into smaller simplier 
  components.

* [Making a specific Django app faster](http://reinout.vanrees.org/weblog/2014/05/06/making-faster.html)
  is a Django performance blog post with some tips on measuring performance
  and optimizing based on the measured results.

* [Django Debug Toolbar](http://django-debug-toolbar.readthedocs.org/en/1.2/) 
  is a powerful Django ORM database query inspection tool. Highly recommended
  during development to ensure you're writing reasonable query code. 
  [Django Silk](http://mtford.co.uk/blog/2/) is another inspection tool and
  has capabilities to do more than just SQL inspection.

## Django视频
* [GoDjango](https://godjango.com/) 提供怎样构建Django应用的免费短视频教程。

* Ontwik在 [Django分类](http://ontwik.com/category/django/) 有视频教程。

* [Designing Django's Migrations](http://pyvideo.org/video/2630/designing-djangos-migrations)
  covers Django 1.7's new migrations from the main programmer Andrew Godwin.

* DjangoCon US videos from 
  [2013](http://www.youtube.com/user/TheOpenBastion/videos), 
  [2012](http://pyvideo.org/category/23/djangocon-2012), 
  [2011](http://pyvideo.org/category/3/djangocon-2011), as well as  
  [earlier US and DjangoCon EU conferences](http://pyvideo.org/category) are
  all available free of charge.


## 使用Django的开源项目案例
* [Txt 2 React](https://github.com/makaimc/txt2react) is a full Django web
  app that allows audiences to text in during a presentation with feedback
  or questions.

* [Openduty](https://github.com/ustream/openduty) is a website status checking
  and alert system similar to PagerDuty.


## Django学习清单
<i class="fa fa-check-square-o"></i> 
在你的本地开发环境中[安装Django](https://docs.djangoproject.com/en/dev/topics/install/)

<i class="fa fa-check-square-o"></i> 
将Django的第一个 
["投票"教程](https://docs.djangoproject.com/en/dev/intro/tutorial01/) 从头到尾做一遍。
 
<i class="fa fa-check-square-o"></i> 
借助教程和上面的Django资源做一个稍稍复杂的应用。

<i class="fa fa-check-square-o"></i> 
在 [官方文档](https://docs.djangoproject.com/en/dev/) 和上面提到的资源链接的帮助下开始自己的Django项目之旅。你可能会遇到不少挫折，不过这些对你通往正确的应用开发之路来说是至关重要的。

<i class="fa fa-check-square-o"></i> 
阅读 [2 Scoops of Django](http://www.amazon.com/Two-Scoops-Django-Best-Practices/dp/098146730X/ref=sr_1_2?ie=UTF8&qid=1391562062&sr=8-2&tag=mlinar-20) 这本书理解Django的最佳实践并学会用更好的方式来构建Django web应用。

<i class="fa fa-check-square-o"></i> 
移步 [部署小节](/deployment.html) 把你的Django应用发布到网上。

### 看看自己写的Django应用，接下来你想学点什么呢？
