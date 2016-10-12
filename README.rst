buildout-base
=============

Generic zc.buildout base config files, which can individually included in other buildouts.


Installing Plone on Debian based systems
----------------------------------------

You might need these::

    $ sudo apt-get install build-essential libreadline-dev zlib1g-dev libbz2-dev
    $ sudo apt-get install libssl-dev libjpeg-dev


Plone 2.5 and other oldies information
--------------------------------------

On Debian you might need to link a freetype2 lib to freetype in order to get Pillow working::

    sudo ln -s /usr/include/freetype2 /usr/local/include/freetype

Also see: http://unix.stackexchange.com/questions/105265/install-pil-pillow-via-pip-in-debian-testing-jessie

