title: Flask
category: page
slug: flask
sort-order: 023
choice1url: /deployment.html
choice1icon: fa-share fa-inverse
choice1text: 我已经用Flask写好一个web应用了，怎么部署呢？
choice2url: /web-frameworks.html
choice2icon: fa-code fa-inverse
choice2text: 我想回头看看其他的web框架。
choice3url: /cascading-style-sheets.html
choice3icon: fa-css3 fa-inverse
choice3text: 用户界面非常糟糕，我怎样美化我的web应用呢？
choice4url: /source-control.html
choice4icon: fa-code-fork fa-inverse
choice4text: 我如何控制、管理我的源代码不使其丢失呢？


# Flask
[Flask](http://flask.pocoo.org/)是一个以“[核心微小但易于扩展](http://flask.pocoo.org/docs/design/)”为核心理念的web框架。

## 为什么Flask是个不错的选择？

Flask通常被认为比Django更为[Python化（Pythonic）](http://stackoverflow.com/questions/58968/what-defines-pythonian-or-pythonic) ，因为Flask web框架的代码更为明确（译者注：原文because Flask web application code is by and large more explicit.）。另外Flask由于它基本没有固定范例的束缚，新手可以随心所欲的写一个简单的应用来运行。

举个例子，下面是一个用Flask写的“hello world”应用，相比Django应该要省掉很多代码：

    from flask import Flask
    app = Flask(__name__)

    @app.route('/')
    def hello_world():
        return 'Hello World!'

    if __name__ == '__main__':
        app.run()

Flask是在Django之后好几年才开发出来的，因此看看随着这个框架的演进，Python社区都有哪些反应呢？
Jökull Sólberg在 [experience switching between Flask and Django](http://jokull.calepin.co/my-flask-to-django-experience.html) 这篇文章中对这方面写的很清楚。

## Flask资源
由18部分组成的这份Flask mega教程对Flask框架初学者来说绝对是极好的资源。诚然，这个系列教程的文章略多，不过每一篇文章都专注于一个单独的主题而且也不失难度，总之整个系列都值得精读一番。另外这个教程的[作者](https://twitter.com/miguelgrinberg)也写了一本叫作 [O'Reilly Flask Web Development](http://shop.oreilly.com/product/0636920031116.do) 的书，是不是也考虑去买回来读一读呢？［译者注：如下教程已有[中文版](http://www.pythondoc.com/flask-mega-tutorial/index.html)，故这里就不做翻译。］

  * [Part 1: Hello World](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
  * [Part 2: Templates](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-ii-templates)
  * [Part 3: Web Forms](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iii-web-forms)
  * [Part 4: Database](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iv-database)
  * [Part 5: User Logins](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-v-user-logins)
  * [Part 6: Profile Page and Avatars](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-vi-profile-page-and-avatars)
  * [Part 7: Unit Testing](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-vii-unit-testing)
  * [Part 8: Followers, Contacts, and Friends](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-viii-followers-contacts-and-friends)
  * [Part 9: Pagination](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-ix-pagination)
  * [Part 10: Full Text Search](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-x-full-text-search)
  * [Part 11: Email Support](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xi-email-support)
  * [Part 12: Facelift](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xii-facelift)
  * [Part 13: Dates and Times](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xiii-dates-and-times)
  * [Part 14: I18n and L10n](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xiv-i18n-and-l10n)
  * [Part 15: Ajax](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xv-ajax)
  * [Part 16: Debugging, Testing and Profiling](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xvi-debugging-testing-and-profiling)
  * [Part 17: Deployment on Linux](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xvii-deployment-on-linux-even-on-the-raspberry-pi)
  * [Part 18: Deployment on the Heroku Cloud](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xviii-deployment-on-the-heroku-cloud)

* [Flask扩展列表](http://flask.pocoo.org/extensions/) 提供一份优质的用来扩展Flask功能的包列表。当你觉得使用核心框架不能很好的解决问题时，最好先去看一下这个列表。

* Randall Degges 写了一篇叫
  [30分钟写一个Flask应用](https://stormpath.com/blog/build-a-flask-app-in-30-minutes/) 的攻略

* Jeff Knupp 写的 [将Flask投入生产环境](http://www.jeffknupp.com/blog/2014/01/29/productionizing-a-flask-application/) 这篇文章也非常好。

* [用Flask写一个网站](http://maximebf.com/blog/2012/10/building-websites-in-python-with-flask/#.U06EZ-ZdW4J) 是一个起步教程，但你的应用变得复杂起来时下面这篇文章可以参考一下。
  [随着Flask应用的变得复杂](http://maximebf.com/blog/2012/11/getting-bigger-with-flask/)。


* The Plank & Whittle博客上有两篇文章， 一篇叫 
  [打包一个Flask应用](http://www.plankandwhittle.com/packaging-a-flask-web-app/) ，另一篇叫
  [用Debian包管理系统打包一个Flask应用](http://www.plankandwhittle.com/packaging-a-flask-app-in-a-debian-package/)。当你写好一个Flask应用，部署的时候可能会用到。

* The Tuts+ 的 [Flask教程](http://code.tutsplus.com/tutorials/an-introduction-to-pythons-flask-framework--net-28822) 也是一个Flask起步教程。

* [Flask by Example: 第一部分](http://www.realpython.com/blog/python/flask-by-example-part-1-project-setup/) 展示了开展一个 Flask 项目的基础步骤 ，
  [第二部分](http://www.realpython.com/blog/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/) 展示了如何运用PostgreSQL、SQLAlchemy和Alembic。

* [如何组织一个Flask应用代码](https://www.digitalocean.com/community/articles/how-to-structure-large-flask-applications) 这篇文章教你如何如何一步一步往你的Flask应用中增加功能而保持代码结构的清晰。

## 使用Flask的开源项目案例
* [Flask Foundation](https://github.com/JackStouffer/Flask-Foundation) 可以作为开展Flask新项目的起点。

* [Flaskr TDD](https://github.com/mjhea0/flaskr-tdd) 以官方教程为基础增加了测试驱动开发和JQuery的内容。

* 使用 [Flask App Engine Template](https://github.com/kamalgill/flask-appengine-template)
  在Google App Engine上运行Flask应用。

* 这是一个 
  [笔记应用](http://charlesleifer.com/blog/saturday-morning-hack-a-little-note-taking-app-with-flask/)，代码在
  [Gists](https://gist.github.com/coleifer/632d3c9aa6b2ea519384)上。


## Flask框架学习清单
<i class="fa fa-check-square-o"></i> 
在本地开发环境中[安装Flask](http://flask.pocoo.org/docs/installation/)

<i class="fa fa-check-square-o"></i> 
将资源部分的系列教程从头到尾做一遍。
 
<i class="fa fa-check-square-o"></i> 
浏览一遍[Flask Extensions Registry](http://flask.pocoo.org/extensions/)看看哪些扩展能用于你的项目。

<i class="fa fa-check-square-o"></i> 
基于Flask mega教程和其他开源例子，去写一个自己的Flask应用。 

<i class="fa fa-check-square-o"></i> 
移步 [部署小节](/deployment.html) 把你的第一个Flask应用发布到网上。

### 关于web框架的知识，接下来你想学点什么呢？
