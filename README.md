# Magick Installer!

Magick Installer exists for two reasons:

1. installing ImageMagick is hard
2. MacPorts is the devil, and shouldn't be installed just for installing ImageMagick

## How?

    curl https://raw.github.com/liwei78/magick-installer/master/magick-installer.sh | sh

or

Download and run this simple script and watch your ImageMagick support go from 0 to 1 without MacPorts.

## Verified Platforms

* Mac OS X 10.7
* Mac OS X 10.6
* Mac OS X 10.8.4 (liwei test this)

## Support

This script WILL get stale. As mirrors die and versions increase, the download commands in this script may not work anymore. If this happens to you, please fork the script and fix it. Let's keep this working forever!

## liwei 2013-8-16

I forked this repo from https://github.com/maddox/magick-installer, and fix some files location and git add them.

The boring thing is Magick-config missing, and I know it is easy (apt-get, yum, brew, port ...) install magick-wand or libmagickwand-dev for other plantforms, even mac os 10.6.2.

But for 10.8.4 , it's not.

Now I test the script and finally install imagemagic with Magick-config.

Rique Li
