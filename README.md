# Out-of-tree version of Linux menuconfig tool

KConfig is a flexible Linux project configuration mechanism. It allows to
define and use set of configuration options and then build a `.config` file
that takes all the Kconfig dependencies and restrictions into account.

`menuconfig` project provides Kconfig parser and GUI tool to modify the project config.

To build GUI toolset please run
`ninja`

At Arch you can install [menuconfig-git](https://aur.archlinux.org/packages/menuconfig-git/) package
from AUR repository.
