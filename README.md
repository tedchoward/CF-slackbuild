CFLite (CoreFoundation) for Slackware Linux
===========================================

CFLite is an open source version of the CoreFoundation framework
found on Mac OS X and iOS. It is designed to be simple and
portable. For example, it can be used on other platforms to read
and write property lists that may come from Mac OS X or iOS.  It is
important to note that this version is not the exact same version as
is used on Mac OS X or iOS, but they do share a significant amount
of code.

To build, simply run as root

    ./CF.SlackBuild

To install, run (as root)

    installpkg /tmp/CF-365.19-i486-1_ted.txz
