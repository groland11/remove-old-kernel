![last commit](https://img.shields.io/github/last-commit/groland11/do-restarting.svg)
![release date](https://img.shields.io/github/release-date/groland11/do-restarting.svg)
![languages](https://img.shields.io/github/languages/top/groland11/do-restarting.svg)
![license](https://img.shields.io/github/license/groland11/do-restarting.svg)

# remove-old-kernel
Remove old kernel packages from Red Hat Enterpise Linux 7+
- Keeps at least one old kernel. Oldest kernel versions will be deleted first.
- Only deletes old kernel packages if disk space on /boot is low.
- Does not remove kernel packages in debug mode.

## Usage
```
./remove-old-kernel.py -h
usage: remove-old-kernel.py [-h] [-d] [-V]

Remove old kernel packages to free up disk space on /boot

optional arguments:
  -h, --help     show this help message and exit
  -d, --debug    generate additional debug information
  -V, --version  show program's version number and exit
```

## Example
