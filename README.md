# Intervention Coding Standard

Coding Standard for PHP projects of [Intervention](https://intervention.io).

## Installation

Install the package using [Composer](https://getcomposer.org) by running the following command:

```bash
composer require intervention/coding-standard
```

## Getting Started

After Installation add `<rule ref="Intervention"/>` to your `phpcs.xml`.

Your configuration might look like this:

```
<?xml version="1.0"?>
<ruleset xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">

    <arg name="extensions" value="php"/>
    <file>./src</file>

    <rule ref="Intervention"/>

</ruleset>
```

[PHP_CodeSniffer](https://github.com/PHPCSStandards/PHP_CodeSniffer) is
automatically installed along with this package. So you can easily check the
standard with the following command.

```
./vendor/bin/phpcs
```
