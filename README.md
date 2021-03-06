![Simple MVC Framework](http://simplemvcframework.com/app/templates/publicthemes/smvc/images/logo.png)

## Packagist

[![Join the chat at https://gitter.im/simple-mvc-framework/framework](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/simple-mvc-framework/framework?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Software License](http://img.shields.io/badge/License-BSD--3-brightgreen.svg?style=flat-square)](LICENSE)
[![Total Downloads](https://img.shields.io/packagist/dt/simple-mvc-framework/v2.svg?style=flat-square)](https://packagist.org/packages/simple-mvc-framework/v2)
[![Dependency Status](https://www.versioneye.com/user/projects/554367f738331321e2000005/badge.svg?style=flat)](https://www.versioneye.com/user/projects/554367f738331321e2000005)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/simple-mvc-framework/v2/master/license.txt)
[![GitHub stars](https://img.shields.io/github/stars/simple-mvc-framework/framework.svg)](https://github.com/simple-mvc-framework/framework/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/simple-mvc-framework/framework.svg)](https://github.com/simple-mvc-framework/framework/network)

The framework is now on packagist [https://packagist.org/packages/simple-mvc-framework/v2](https://packagist.org/packages/simple-mvc-framework/v2)

Install from terminal now by using:

````
composer create-project simple-mvc-framework/v2 foldername -s dev
````

The foldername is the desired folder to be created.

#V2.2
#What is Simple MVC Framework?

Simple MVC Framework is a PHP 5.5 MVC system. It's designed to be lightweight and modular, allowing developers to build better and easy to maintain code with PHP.

The base framework comes with a range of helper classes.

## Documentation

Full docs & tutorials are available at [simplemvcframework.com](http://simplemvcframework.com)

##Requirements

 The framework requirements are limited

 - Apache Web Server or equivalent with mod rewrite support.
 - PHP 5.5 or greater is required

 Although a database is not required, if a database is to be used the system is designed to work with a MySQL database. The framework can be changed to work with another database type.

## Installation

1. Download the framework
2. Unzip the package.
3. To run composer, navigate to your project on a terminal/command prompt then run 'composer install' that will update the vendor folder. Or use the vendor folder as is (composer is not required for this step)
Upload the framework files to your server. Normally the index.php file will be at your root.
4. Open the app/Core/routes.php file with a text editor, setup your routes.
5. Open app/Core/Config.example.php and set your base path (if the framework is installed in a folder the base path should reflect the folder path /path/to/folder/ otherwise a single / will do. and database credentials (if a database is needed). Set the default theme. When you are done, rename the file to Core/Config.php
6. Edit .htaccess file and save the base path. (if the framework is installed in a folder the base path should reflect the folder path /path/to/folder/ otherwise a single / will do.

### Other Contributions
Have you found this library helpful? Why not take a minute to endorse my hard work on [coderwall](https://coderwall.com/daveismynamecom)! Just click the badge below:

[![endorse](https://api.coderwall.com/daveismynamecom/endorsecount.png)](https://coderwall.com/daveismynamecom)
