MythTPL
=========

By Shu Saura  
Based on RainTPL 3 by Federico Ulfo

[MythTPL](https://github.com/shusaura85/mythtpl) is an easy template engine for PHP that allows easy separation of the presentation from the logic.

Features
--------
* Simple syntax
* Easy to use
* Fast, templates are compiled to plain PHP code
* Powerful, modifiers and operations with variables
* Extensible, you can register new tags

Supported tags
--------
* {$variable} to include a variable in the template
* {#CONSTANT} or {#'string'} to include a constant or string
* {if} for conditional blocks
* {loop} to loop over arrays
* {include} to include another template
* {ignore} to add private comments in the template
* {noparse} to not process tags contained inside
* {function} to run a PHP function
* {php} if you really must use PHP inside your templates (disabled by default in configuration)
* {autoescape} to automatically escape all tag values inside
* {elseif} {else} {break} {continue} to use with conditional or looping tags


Installation / Usage
--------------------

* Using **Composer**

    ``` shell
    composer require shusaura85/mythtpl
    ```
* Manually

    ``` php
    require '/path/to/src/autoload.php'
    ```


Requirements
-------------
MythTPL requires at least `PHP 7.4` to work. MythTPL has no external dependencies.


Licence
-------

MythTPL is published under the MIT Licence, see `LICENSE` file for details.

