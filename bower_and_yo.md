Bower/Yeoman
===============

Who are you ?
----------

Yosuke!

![icon](https://si0.twimg.com/profile_images/206948941/wall-e.jpg)

Working at : [![dena](https://www.e2r.jp/export/ja/dena2014/images/dena_logo.png)](http://dena.com/)

Twitter : [@yosuke_furukawa](https://twitter.com/yosuke_furukawa)

Blog : [from scratch](http://yosuke-furukawa.hatenablog.com/)

Community : [![node](http://joyeur.files.wordpress.com/2011/11/node_logo-01.png)](http://nodejs.jp/)


What is Bower ?
-----------------

<a href="http://bower.io/"><img src="bower-logo.png" style="width:20%; height:20%;" /></a>


- client side package manager.

- (It is like NPM on client side.)


Super Fast Bower Demo
-----------------
<!-- data-scale="3"  -->
<!-- data-rotate="90" -->

Install
-----------------

    $ npm install -g bower

※ if you dont have npm, you would install node.js to be better.


Install
-----------------

    $ bower init // create bower.json
    $ bower install jQuery // install latest version
    $ bower install underscore#1.4.3 // specify version
    $ bower install backbone --save // write bower.json

install them to *./components/[package_name]*.

**--save** option save the package to bower.json

you dont need to type **"wget"** any more!!

Update
-----------------

    $ bower update // update libraries

search modules
----------------

    $ bower search backbone

OR

    $ bower lookup backbone

get more infomation
----------------

    $ bower info backbone


If you have cool client modules
----------------

    $ bower register <module name> <git repository>

※ use **git tag** and put versions like **0.0.1**, **0.0.2**.

HOWEVER, Bower has some **uncool** points...
-----------------

html script and link
-----------------

    <script src="/components/jquery/jquery.js" />
    <script src="/components/impress.js/js/impress.js" />

bower does not have layout manager...

Use **grunt-bower-task**
----------------

[grunt-bower-task](https://github.com/yatskevich/grunt-bower-task) can align our js/css to be better.

    lib
    |-- js
    |   |- jquery
    |   |  |- jquery.js
    |   |
    |   \- impress
    |      |- impress.js
    |-- css
        \- impress
           |- impress.css

YEAH !!
----------------

    <link href="css/bootstrap.css" />
    <script src="js/jquery.js" />
    <script src="js/impress.js" />

<h3>So simple. </h3>

Yeoman
---------------

- task runner => 
<a href="http://gruntjs.com/"><img src="http://gruntjs.com/img/grunt-logo.svg" style="width:20%; height:20%;"/></a>

- frontend package manager => 
<a href="http://bower.io/"><img src="bower-logo.png" style="width:20%; height:20%;" /></a>

- backend package manager => 
<img src="https://npmjs.org/static/npm.png" style="width:20%; height:20%;" />


So you want to create your own templates??
--------------

![yeoman](http://yeoman.io/assets/img/yeoman-logo.png)

yeoman can generate application templates.

DEMO
-------------

<a href="http://www.yosuke-furukawa.info:5000/">demo site</a>

Summary
-----------

+ **Bower** is useful tool.
+ but Bower is not so cool, **grunt-bower-task** is really helpful.
+ **Yeoman** can generate your application templates.
+ I am creating our own templates for **jsCafe**!!

DeNA NEEDS YOU!!!
-------
+ *JavaScript Engineers*
+ *Noders*
+ *Designers*
+ [Join us!!!!](http://dena.com/recruit/)
![dena](https://www.e2r.jp/export/ja/dena2014/images/dena_logo.png)

