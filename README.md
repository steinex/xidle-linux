# xidle-linux
OpenBSD's xidle for Linux

This is xidle taken from OpenBSD with a few changes to make it usable for Linux users/packagers:
* GNU Make compatible Makefile, by Konstantin Shalygin
* Removed pledge() from the source

Since xidle is developed and maintained as part of the OpenBSD base system and not released independently, I will do releases matching the version number of the OpenBSD release xidle came from.
