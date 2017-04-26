# wkhtmltox-linux-generic-amd64
## What is it?
wkhtmltopdf and wkhtmltoimage are open source (LGPLv3) command line tools to render HTML into PDF and various image formats using the Qt WebKit rendering engine. These run entirely "headless" and do not require a display or display service.

There is also a C library, if you're into that kind of thing.

This repository was made for use in Packagist with composer.

## Installation?
1. Install composer
2. Check requirements: `zlib, fontconfig, freetype, X11 libs (libX11, libXext, libXrender)`
3. Require it with:
```
composer require azazppl/wkhtmltox-linux-generic-amd64
```

The binaries will be located at:
```
vendor/AzaZPPL/wkhtmltox-linux-generic-amd64/bin/wkhtmltopdf
vendor/AzaZPPL/wkhtmltox-linux-generic-amd64/bin/wkhtmltoimage
```

Two symlinks will be created in the /bin folder

```
vendor/bin/wkhtmltopdf
vendor/bin/wkhtmltoimage
```
