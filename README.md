# ArrayAccess Trait
PHP Trait to implement [ArrayAccess](http://php.net/manual/de/class.arrayaccess.php "PHP ArrayAccess")

## Installation

First, pull in the package through Composer.

Run `composer require hepplerdotnet/arrayaccess`

And then include the Trait within your Class to implement [ArrayAccess](http://php.net/manual/de/class.arrayaccess.php "PHP ArrayAccess").

```php
class Foo implements \ArrayAccess
{
use \HepplerDotNet\ArrayAccess\ArrayAccess;
...
}
```
That's it, your Class can now use [ArrayAccess](http://php.net/manual/de/class.arrayaccess.php "PHP ArrayAccess").
