# Standard country or area codes for statistical use (M49)

[![GitHub license](https://img.shields.io/github/license/fawno/UN-M49)](https://github.com/fawno/UN-M49/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/fawno/UN-M49)](https://github.com/fawno/UN-M49/releases)
[![Packagist](https://img.shields.io/packagist/v/fawno/un-m49)](https://packagist.org/packages/fawno/un-m49)
[![Packagist Downloads](https://img.shields.io/packagist/dt/fawno/un-m49)](https://packagist.org/packages/fawno/un-m49/stats)
[![GitHub issues](https://img.shields.io/github/issues/fawno/UN-M49)](https://github.com/fawno/UN-M49/issues)
[![GitHub forks](https://img.shields.io/github/forks/fawno/UN-M49)](https://github.com/fawno/UN-M49/network)
[![GitHub stars](https://img.shields.io/github/stars/fawno/UN-M49)](https://github.com/fawno/UN-M49/stargazers)
[![PHP](https://img.shields.io/packagist/php-v/fawno/un-m49)](https://php.net)

 [Standard country or area codes for statistical use (M49)](https://unstats.un.org/unsd/methodology/m49/)

## Requirements
 - PHP >= 7.4.0

## Installation

You can install this plugin into your application using
[composer](https://getcomposer.org):

```
  composer require fawno/un-m49
```

## Usage

```php
use UN\M49\English\ISOalpha3Names as ISOalpha3NamesEnglish;
use UN\M49\Spanish\ISOalpha3Names as ISOalpha3NamesSpanish;
use UN\M49\French\ISOalpha3Names as ISOalpha3NamesFrench;
use UN\M49\Russian\ISOalpha3Names as ISOalpha3NamesRussian;
use UN\M49\Chinese\ISOalpha3Names as ISOalpha3NamesChinese;
use UN\M49\Arabic\ISOalpha3Names as ISOalpha3NamesArabic;
use UN\M49\ISOalpha3;

// Get ISO-alpha3 code from M49 code
echo ISOalpha3::fromM49(724), PHP_EOL;

// Get English name from M49 code
echo ISOalpha3NamesEnglish::fromM49(724), PHP_EOL;

// Get Spanish name from M49 code
echo ISOalpha3NamesSpanish::fromM49(724), PHP_EOL;

// Get French name from M49 code
echo ISOalpha3NamesFrench::fromM49(724), PHP_EOL;

// Get Russian name from M49 code
echo ISOalpha3NamesRussian::fromM49(724), PHP_EOL;

// Get Chinese name from M49 code
echo ISOalpha3NamesChinese::fromM49(724), PHP_EOL;

// Get Arabic name from M49 code
echo ISOalpha3NamesArabic::fromM49(724), PHP_EOL;
```

