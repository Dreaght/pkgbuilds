# pkgbuilds

Collection of PKGBUILDs and related files for Arch Linux packages.

## Layout

Each package lives in its own directory and contains its `PKGBUILD` plus any patches or helper files needed to build it.

## Usage

Build a package from its directory with:

```bash
makepkg -si
```

Or with `yay`:

```bash
yay -Bi <dir>
```
