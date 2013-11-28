gentoo-layman
=============

An overlay to install [uwl](https://github.com/lexa-uw/gentoo-layman) in right way in Gentoo Linux.                                                               

Add it to Layman
----------------

To add this overlay you need to add this url to your overlays section of layman.cfg:

    https://raw.github.com/lexa-uw/gentoo-layman/master/layman.xml

It will look something like this:

    overlays  : http://www.gentoo.org/proj/en/overlays/repositories.xml
                https://raw.github.com/lexa-uw/gentoo-layman/master/layman.xml

Then you need to fetch layman overlays list with

    sudo layman -L

And then you can add overlay:

    sudo layman -a phpdaemon

