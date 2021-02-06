# This module allows you to hide default store code from URLs

![Magento Hide Default Store Code](http://i.imgur.com/FVuZL5f.png)

## Feature

http://www.example.com/default/shoes.html

_becomes_

http://www.example.com/shoes.html

## Installation

### Magento CE 1.8.x, 1.9.x

Install with composer:

```bash
composer require klipach/magento-hide-default-store-code
```

## Configuration

* Go to "System > Configuration > Web > Url Options"
* Enable both "Add Store Code to Urls" and "Hide Default Store Code" options
* Clear cache
