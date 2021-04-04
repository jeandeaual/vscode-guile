# VSCode Guile

[![build](https://github.com/jeandeaual/vscode-guile/workflows/build/badge.svg)](https://github.com/jeandeaual/vscode-guile/actions?query=workflow%3Abuild)

[GNU Guile](https://www.gnu.org/software/guile/) syntax highlighting for VSCode.

## Features

* Guile syntax highlighting, based on [vscode-scheme](https://marketplace.visualstudio.com/items?itemName=sjhuangx.vscode-scheme)

## Requirements

* [VSCode](https://code.visualstudio.com/) 1.0.0 or newer

## Installation

1. Open the Extensions left panel in VSCode (Windows: Ctrl+Shift+X; MacOS: Cmd+Shift+X)
2. Type in `Guile` in the search bar
3. Install the extension, then reload VSCode (Ctrl+R)

## Build

```sh
yarn install
npx vsce package
```

## Release Notes

See [here](CHANGELOG.md).
