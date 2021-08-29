# Firefox Browser Developer Edition

The browser made for developers:
All the latest developer tools in beta, plus experimental features like the Multi-line Console Editor and WebSocket Inspector.
A separate profile and path so you can easily run it alongside Release or Beta Firefox.
Preferences tailored for web developers: Browser and remote debugging are enabled by default, as are the dark theme and developer toolbar button.

**NOTE:**
This package is a binary repackaging from the official package.

## Use This Script

1. Download this script
2. Download [Firefox Developer Edition for Linux](https://www.mozilla.org/en-US/firefox/developer/)
3. Edit firefox-developer-edition.SlackBuild and replace the version on these two lines with the version string from the bzip2 file you downloaded _(ex: firefox-92.0b7.tar.bz2)_
    * ```29``` `VERSION=${VERSION:-92.0b9}`
    * ```30``` `SRCVER=${VERSION:-92.0b9}`
4. Copy/Move the bzip2 file into the same subdirectory as you unpacked this SlackBuild _(the same directory this file is in)_
5. As root, run `sh ./firefox-developer-edition.SlackBuild`
6. again as root, run `installpkg /tmp/firefox-developer-edition-$VER-x86_64-1_fcm.tgz`
