# pkgbuilds

Collection of PKGBUILDs and related files for Arch Linux packages.

## Usage

Build a package from its directory with:

```bash
makepkg -Csi
```

Refresh [`yay`](https://github.com/jguer/yay):

```bash
yay -Y --gendb
```

For upgrade do once:
```
yay -Y --gendb --devel --save
```
