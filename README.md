
# Electron Windows 10
Link - https://electronjs.org/
This is a guide for installing and building applications with Electron.
This document is based on [Electron Build Instructions for Windows](https://electronjs.org/docs/development/build-instructions-windows#prerequisites).

## References

- **PIP**
*Pythons equivalent of package management, similar to npm, yarn, composer, etc.
PIP comes bundled with an installation of Python 2.7+*
Link - https://pypi.org/project/pip/

## Prerequisites

Please download and install the following:

- Python ( > 2.7.15 & < 3.0.0 )
*Link - https://www.python.org/*

 - Git ( latest )
*Link - https://git-scm.com*

- NodeJS ( latest LTS )
*Link - https://nodejs.org/en/*

- Visual Studio 2017 ( 15.7.2+ )
*Link - https://visualstudio.microsoft.com/vs/*

## Environment Variables & Paths
See [Editing Variables & Paths](https://stackoverflow.com/questions/43415052/how-to-run-a-php-program-from-command-prompt-on-a-windows-machine/43505955#43505955)

Add the following to **System variables**:

|Variable name| Variable Value |
|-------------|----------------|
| WINDOWSSDKDIR | C:\Program Files (x86)\Windows Kits\8.1 |
| GYP_MSVS_OVERRIDE_PATH |  |
| SCCACHE_TWO_TIER | true |

Add the following to **PATH**:



pip install pywin32
