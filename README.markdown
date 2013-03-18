About
-----

***THIS IS A FORK FROM [Squizlabs](https://github.com/squizlabs/PHP_CodeSniffer)...just added a standard for CodeIgniter framework.***

PHP\_CodeSniffer is a PHP5 script that tokenises PHP, JavaScript and CSS files to detect violations of a defined coding standard. It is an essential development tool that ensures your code remains clean and consistent. It can also help prevent some common semantic errors made by developers.

[![Build Status](https://secure.travis-ci.org/squizlabs/PHP_CodeSniffer.png?branch=master)](https://travis-ci.org/squizlabs/PHP_CodeSniffer)

Requirements
------------

PHP\_CodeSniffer requires PHP version 5.1.2 or greater, although individual sniffs may have additional requirements such as external applications and scripts. See the [Configuration Options manual page](http://pear.php.net/manual/en/package.php.php-codesniffer.config-options.php) for a list of these requirements.

The SVN pre-commit hook requires PHP version 5.2.4 or greater due to its use of the vertical whitespace character.

Installation
------------

If you use [Composer](http://getcomposer.org/), include a dependency for `isislabs/php_codesniffer` in your `composer.json` file. For example:

    {
        "require": {
            "isislabs/php_codesniffer": "1.*"
        }
    }

You will then be able to run PHP_CodeSniffer from the vendor bin directory:

    ./vendor/bin/phpcs -h

Documentation
-------------

The documentation for PHP\_CodeSniffer is available in the [PEAR manual](http://pear.php.net/manual/en/package.php.php-codesniffer.php).

Information about upcoming features and releases is available on the [Squiz Labs blog](http://www.squizlabs.com/php-codesniffer).
