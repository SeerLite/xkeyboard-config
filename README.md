# xkeyboard-config-bbkt
[Upstream xkeyboard-config](https://gitlab.freedesktop.org/xkeyboard-config/xkeyboard-config) sources patched with @DreymaR's [Big Bag mods](https://github.com/DreymaR/BigBagKbdTrixXKB).

Should build just like the upstream version.

## Why?
* Up-to-date.
* Easy to package. You can use your distribution's official xkeyboard-config package as a base.
* Isn't overwritten on each update (in contrast with the official installation script).
* Has `caps:escape_shifted_capslock` :)

## Installation
AUR package: [`xkeyboard-config-bbkt-git`](https://aur.archlinux.org/packages/xkeyboard-config-bbkt-git/)

Other distros: Soon™

# Packaging
Use your distribution's existing `xkeyboard-config` package as a base but replace the source URL to either of the tar archives from the latest [release](https://github.com/SeerLite/xkeyboard-config-bbkt/releases).
You'll have to make `xkeyboard-config-bbkt` a package that conflicts and/or replaces the official `xkeyboard-config` package.

## See also
[Upstream README](./README)

[Dreymar's Big Bag of Keyboard Tricks main page](https://dreymar.colemak.org/index.html)
