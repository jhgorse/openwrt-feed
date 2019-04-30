============
OpenWrt Feed
============

This branch is make for barrier breaker and an CMake 2.8.x.

.. contents::

Packages
========

* `openwrt-feed <https://github.com/jhgorse/openwrt-feed>`_ (with useful additional modules support)

How to use
==========

Add the following line to the feeds.conf in the OpenWrt buildroot::

    src-git jhgorse https://github.com/jhgorse/openwrt-feed

Update the feed::

    ./scripts/feeds update jhgorse

Activate the package::

    ./scripts/feeds install PACKAGE_NAME

Installed packages should now appear in make menuconfig.

