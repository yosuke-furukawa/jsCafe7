Bower/Yeoman
===============

Presentation is here!!
----------
[http://goo.gl/46dk3](http://goo.gl/46dk3)

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
    |   |- jquery.js
    |   \- impress.js
    |-- css
        \- bootstrap.css

YEAH !!
----------------

    <link href="css/bootstrap.css" />
    <script src="js/jquery.js" />
    <script src="js/impress.js" />

<h3>So simple. </h3>

Yeoman
---------------


