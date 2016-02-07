
              
###Non-programmers Introduction to Flask:
  
If you're new to web development, and considering Python as your language of choice, check out Flask. With just a basic knowledge of Python, Flask can make it easy to get up and running and creating web content - and much quicker than if you were just using Python by itself.

Although it is possible to jump right into Flask and go through some tutorials to create web apps right away, having a basic grasp of the following concepts will speed up your learning curve by creating a mental foundation for understanding Flask: 

**Framework** 

A framework is basically a set of software tools that take care of common tasks necessary for the development of web applications or sites. These tasks include accessing databases, managing sessions, creating displays of HTML and using templating. Think of templating as a way to change the content of a web page or html element within a page while keeping the template or area where the changes occur constant. A common example would be a news site that changes the latest stories when you visit them at different times of day. 

 
**Microframework**

A microframework is a framework that has a minimal number of integrated libraries or tools, but gives you the option of "bolting on" pre-existing libraries that add functionality to your application. This is what Flask's documentation means when it says that it is "extensible". Extensibility makes it easier to get started using a framework, as you can incorporate different tools only as they are needed.

**Jinja2**

Jinja2 is a template engine for Python. This library allows for different data to populate common templates through the use of programming logic, like in the new website example mentioned above. To get a better grasp of Jinja templates check out [these examples](https://realpython.com/blog/python/primer-on-jinja-templating)

 

**Werkzeug** 

Werkzeug is a set of utilities for applications that communicate through an interface specification called WSGI (Web Server Gateway Interface). As Werkzeug's documentation states: "WSGI itself is a protocol or convention that ensures that your web application can speak with the web server and more importantly that web applications work nicely together." [This Werkzeug tutorial](http://werkzeug.pocoo.org/docs/0.11/tutorial/#introducint-shortly) can get you up and running on werkzeug if you're interested. 

If you look at the documentation for werkzeug and jinja2 you can get to some pretty simple tutorials that can get you started. Then do a wider search for tutorial videos on Flask and you'll see some presentations of the capabilities of flask and get a feel for its potential. 



    ~ What is Flask?

      Flask is a microframework for Python based on Werkzeug
      and Jinja2.  It's intended for getting started very quickly
      and was developed with best intentions in mind.

    ~ Is it ready?

      It's still not 1.0 but it's shaping up nicely and is
      already widely used.  Consider the API to slightly
      improve over time but we don't plan on breaking it.

    ~ What do I need?

      All dependencies are installed by using `pip install Flask`.
      We encourage you to use a virtualenv. Check the docs for
      complete installation and usage instructions.

    ~ Where are the docs?

      Go to http://flask.pocoo.org/docs/ for a prebuilt version
      of the current documentation.  Otherwise build them yourself
      from the sphinx sources in the docs folder.

    ~ Where are the tests?

      Good that you're asking.  The tests are in the
      tests/ folder.  To run the tests use the
      `py.test` testing tool:

        $ py.test

    ~ Where can I get help?

      Either use the #pocoo IRC channel on irc.freenode.net or
      ask on the mailinglist: http://flask.pocoo.org/mailinglist/

      See http://flask.pocoo.org/community/ for more resources.


