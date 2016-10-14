# tejasext
Sample extenstion for Yii2
Hello World
===========
Just A Hello World Yii2 Extension  

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist tejasext/hello-world "*"
```

or add

```
"tejasext/hello-world": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php 
<?php
use tejasext\HelloWorld;
?>
<?= HelloWorld\SayHello::world();  ?>
```
