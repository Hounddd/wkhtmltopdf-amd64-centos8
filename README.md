wkhtmltopdf for CentOS 8
================

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/) for CentOS 8 amd64.  
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package with:

    composer require hounddd/wkhtmltopdf-amd64-centos8 "0.12.6"

The binary will then be located at:

    vendor/hounddd/wkhtmltopdf-amd64-centos8/bin/wkhtmltopdf-amd64-centos8

Also a symlink will be created in your configured bin/ folder:

    vendor/bin/wkhtmltopdf-amd64-centos8

## Infos

Ruby gems containing easily installable access to wkhtmltopdf application can be found at [zakird/wkhtmltopdf_binary_gem](https://github.com/zakird/wkhtmltopdf_binary_gem/tree/master/bin)