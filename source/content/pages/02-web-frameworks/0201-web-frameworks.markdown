title: Web Frameworks
category: page
slug: web-frameworks
sort-order: 021
choice1url: /django.html
choice1icon: fa-terminal fa-inverse
choice1text: 告诉我更多关于Django框架的知识。
choice2url: /flask.html
choice2icon: fa-flask
choice2text: 我想了解更多关于Flask框架的知识。
choice3url: /bottle.html
choice3icon: fa-tint fa-inverse
choice3text: 给我看看更多关于Bottle框架的资料吧。
choice4url: /other-web-frameworks.html
choice4icon: fa-question fa-inverse
choice4text: 还有更多Python的web框架没有？


# web框架
web框架就是让开发者可以更简单地构建可靠的、可扩展的、可维护的web应用的代码库。

## 为什么有必要使用web框架
web框架包含了开发者在过去二十年构建动态web应用中得到的经验教训。框架的使用使得通用HTTP操作的代码复用变得简单，也是组织代码变得更为容易，因此提高了代码的可维护性。

## 常见的web框架功能
框架会通过其本身的代码提供许多功能，也会通过扩展来实现运行一个web应用所需要的常用操作。这些常见的操作包括：

1. URL路由
2. 提供输出HTML、XML、JSON等等格式的模版
3. 操作数据库
4. 提供防范诸如跨站请求伪造（CSRF）等等攻击的手段

当然，不是所有web框架都提供上述功能，框架从实现简单的单一用例到包罗万象不一而足，当然对于每个开发者来说复杂度也在提升。一些框架通过“内置电池”的方法来使实现任何功能变得可能，一些则仅仅提供最小化的代码库依靠扩展来实现前者想要实现的功能。

举个例子，Django这个web应用框架内置了一个对象关系映射（ORM）层来抽象关系型数据库的读、写、查询、删除操作。但是，Django的这个ORM层如果不经过大量修改，怕是很难很好的与诸如[MongoDB](http://www.mongodb.org/)这样的非关系型数据库协作。
一些其他的框架诸如Flask和Pyramid则可以通过导入Python外部库从而更容易的使用非关系型数据库。通常，提供最小化功能而易于扩展的框架和所有功能紧密耦合的框架是框架的两大分野。

## web框架资源概况
* [Jeff Knupp](https://twitter.com/jeffknupp)写的"[web框架是什么?](http://www.jeffknupp.com/blog/2014/03/03/what-is-a-web-framework/)"这篇文章深入地解释了web框架是什么，以及与web服务器的关系。

* 查看Stack Overflow上关于
  "[web框架是什么？它相比LAMP怎么样？](http://stackoverflow.com/questions/4507506/what-is-a-web-framework-how-does-it-compare-with-lamp)"这个问题的答案。

* [Python web框架一览](http://www.konstruktor.ee/blog/python-web-framework-roundup/)
  介绍了包含Django、Flask、Bottle以及一些其他知名度较低的框架。

## web框架学习清单
<i class="fa fa-check-square-o"></i> 
初学框架的时候，选择一个主流的框架 （推荐[Django](/django.html)或者[Flask](/flask.html)）深入学习，而不是企图理解每一种框架的用法。

<i class="fa fa-check-square-o"></i> 
去框架的资源链接里找一个复杂详细的教程深入地学习。

<i class="fa fa-check-square-o"></i> 
去学习一下那些使用你心仪的框架开发出来的开源应用的代码，也许他们的代码也可以用到你的应用中去呢。

<i class="fa fa-check-square-o"></i> 
去写出你的第一个简单的web应用，然后到[部署](/deployment.html)这一节去把它放到网上吧。

### 你想学哪一种web框架呢？
