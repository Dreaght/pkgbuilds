# pkgbuilds

Collection of PKGBUILDs and related files for Arch Linux packages.

## Usage

Build a package from its directory with:

```sh
makepkg -Csi
```

Update .SRCINFO:
```sh
makepkg --printsrcinfo > .SRCINFO
```

Refresh [`yay`](https://github.com/jguer/yay):

```sh
yay -Y --gendb
```

For upgrade do once:
```sh
yay -Y --gendb --devel --save
```
