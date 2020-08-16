# Frequently asked questions

## Does it use its own repos

Only instantOS related packages are hosted in the instantOS custom repo, for
everything else the Arch repos are used.

## Does it support 32 bit

Yes, but the 32 bit version doesn't have a live session yet so you'll have to
use the CLI installer

## Raspberry Pi

There are some people working on an arm community edition.
Development is happening on [GitHub](https://github.com/instantOS/instantOS-arm)

## I want to use instantOS software on my Distro

At the moment, getting everything to work on instantOS has priority, but after
the first stable release of instantOS, instantOS programs will be adjusted to
work on other Distros too, Arch and Manjaro first, followed by Debian-based and
NixOS.

## Can I change keybindings

Yes, but just know that you shouldn't before learning the default bindings.
You can clone the git repo of instantWM and edit config.def.h à la dwm.
After that you can run the ./build.sh script to apply changes.
If you have a general suggestion on how to improve bindings, opening an issue on
GitHub is much appreciated.
Patching instantWM is also problematic because you'll manually have to apply updates
and providing support for a copy with modified source code it difficult.
A more traditional runtime config file for hotkeys is being worked on.

