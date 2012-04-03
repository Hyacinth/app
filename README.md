Phundament 3 App
================

Get Phundament 3 - the Yii Application Foundation with CMS features via composer.
For more details visit http://phundament.com

Installation(*)
---------------

Download and extract the installer as ZIP or TAR.GZ file from

* https://github.com/phundament/app/zipball/master
* https://github.com/phundament/app/tarball/master

Enter the app root folder

```
cd phundament-app
```

Get the packages with composer

```
php composer.phar install
```

Run the setup script, if you do not have a copy of Yii Framework (>1.1.10), download it from http://www.yiiframework.com/download/

```
./p3/setup.sh /path/to/yii/framework/yiic
```

Edit *index.php* and include only the p3/config.php file.

```
$config=dirname(__FILE__).'/p3/config.php';
```


 (*) Tested on Mac OS X (Linux)
 
 
Troubleshooting
---------------
 
 * Make sure you have git (http://git-scm.com/) and hg (http://mercurial.selenic.com/) installed
 * zlib extension or unzip available on your PATH
 * OpenSSL Support enabled in PHP
 * ```php -d allow_url_fopen=1 -d memory_limit=64M composer.phar update```
 * Tested on Windows with WAMPSERVER 2.2 (PHP 5.3.10)