# Ollie's custom packages

A repo of PKGBUILD's for my arch install, for patching official/AUR packages, or building from github repo's without license.

## Usage

Add:
```
[REPONAME]
Git = https://github.com/locked-out/custom_packages/
Depth = 2
```

To `paru.conf` and run `paru -Sya` to sync the repo!

## Current Packages

### mipsy

A mips emulator used by used by UNSW. Currently has no licence, so it can't be added to the AUR.

Source: <https://github.com/insou22/mipsy>
