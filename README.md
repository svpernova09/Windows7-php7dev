# Windows 7 PHP 7 Dev Vagrant

## Purpose

Quickly spin up a Windows 7 environment for building PHP 7 to help with the [gophp7-ext](http://gophp7.org/gophp7-ext/) initiative.

## Set up

* Clone this repo
* cd to this folder
* ```vagrant up```

### The Windows Vagrant box is 7.6G!

The first time you run ```vagrant up``` could take a while to download the box file.

## Included Software

* 7zip
* Git
* Microsoft Visual Studio Express 2013
* [php sdk dependencies](http://windows.php.net/downloads/php-sdk/)

## Acknowledgements & Considerations

The base image of this box is from [Modern.ie](https://www.modern.ie) By using this image you are bound to the Windows 7 End Use License Agreement. A link to this agreement and other [Modern.IE notes can be found here](http://modernievirt.blob.core.windows.net/vhd/release_notes_license_terms_1_5_15.pdf). You are also bound to the license agreements of the included software (See list above).

I am not a Windows expert by any stretch. If you can help make this faster / smaller / better please feel free to open a pull request or issue.

## Getting Help

The [PHP Wiki](https://wiki.php.net/internals/windows) may be able to help with your issue. Please open an issue or ask for help in #gophp7-ext on the Freenode IRC network.

## TODO

* Feedback! Please open issues!

## Thank you VERY MUCH to [Carsten Brandt](https://github.com/cebe) for hosting our .box file!
