Blood Donor Management System
=================================

The website helps us find the blood donors along with the details to contact them. People can register in the website during which their blood group is also asked. Users who wish to donate blood can attend the Blood Doation camps which is shown in the "Up Coming Events" if any. 

MOTIVATION
----------

In the present days we often meet people who are in search of blood donors and the situations are very rare that they easily find the donor with the perfect blood group match. They usually struggle a lot. Even the recent trends of communication such as whatsapp do not seem to be helpfull all the time. 

Framework used
--------------

Build with 
	
	> Yii 2 Framework

REQUIREMENTS
------------

The minimum requirement by this project template that your Web server supports PHP 5.4.0.

INSTALLATION
------------

### Install from an Archive File

Extract the archive file downloaded from [yiiframework.com](http://www.yiiframework.com/download/) to
a directory named `basic` that is directly under the Web root.

Set cookie validation key in `config/web.php` file to some random secret string:

```php
'request' => [
    // !!! insert a secret key in the following (if it is empty) - this is required by cookie validation
    'cookieValidationKey' => '<secret random string goes here>',
],
```

You can then access the application through the following URL:

~~~
http://localhost/basic/web/
~~~


### Install via Composer

If you do not have [Composer](http://getcomposer.org/), you may install it by following the instructions
at [getcomposer.org](http://getcomposer.org/doc/00-intro.md#installation-nix).

You can then install this project template using the following command:

~~~
php composer.phar global require "fxp/composer-asset-plugin:~1.1.1"
php composer.phar create-project --prefer-dist --stability=dev yiisoft/yii2-app-basic basic
~~~

Now you should be able to access the application through the following URL, assuming `basic` is the directory
directly under the Web root.

~~~
http://localhost/basic/web/
~~~

CONFIGURATION
-------------

### Database

Edit the file `config/db.php` with real data, for example:

```php
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=yii2basic',
    'username' => 'root',
    'password' => '1234',
    'charset' => 'utf8',
];
```

HOW TO USE?
-----------

The users just have to register with their details and then they can start donating and search for donors. They can further check out their last donated date. The website keeps the users updated about the upcoming events.