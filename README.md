yii2-jalali
===========
Hijri_Shamsi,Solar(Jalali) Date and Time Functions

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist tikasoft/yii2-jalali "*"
```

or add

```
"tikasoft/yii2-jalali": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
in main-local.php add jDate to components array :
 
    'components' => [
        'jDate' => [
            'class' => 'tikasoft\jalali\jDate',
        ],
    ],
	
for use :	
$t=time();
echo  \yii::$app->jDate->dateTime("Y-m-d H:i:s",$t);```