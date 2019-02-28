
# Electron Windows 10
Link - https://electronjs.org/
This is a guide for installing and building applications with Electron.
This document is based on [Electron Build Instructions for Windows](https://electronjs.org/docs/development/build-instructions-windows#prerequisites).

## References

### PIP
Link - https://pypi.org/project/pip/
Pythons equivalent of package management, similar to npm, yarn, composer, etc.
PIP comes bundled with an installation of Python 2.7+

## Prerequisites

Please download and install the following:

- Python ( > 2.7.15 & < 3.0.0 )
*Link - https://www.python.org/*

 - Git ( latest )
*Link - https://git-scm.com*

- NodeJS ( latest LTS )
- https://nodejs.org/en/

## Environment Variables & Paths
See [Editing Variables & Paths](https://stackoverflow.com/questions/43415052/how-to-run-a-php-program-from-command-prompt-on-a-windows-machine/43505955#43505955)

Add the following to **System variables**:
|Variable name| Variable Value |
|-------------|----------------|
| WINDOWSSDKDIR | C:\Program Files (x86)\Windows Kits\8.1 |
| GYP_MSVS_OVERRIDE_PATH |  |
