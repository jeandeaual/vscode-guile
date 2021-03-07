# VSCode Guile

[GNU Guile](https://www.gnu.org/software/guile/) syntax highlighting for VSCode.

## Features

* Guile syntax highlighting, based on [vscode-scheme](https://marketplace.visualstudio.com/items?itemName=sjhuangx.vscode-scheme)

## Requirements

* [VSCode](https://code.visualstudio.com/) 1.44.0 or newer

## Installation

1. Open the Extensions left panel in VSCode (Windows: Ctrl+Shift+X; MacOS: Cmd+Shift+X)
2. Type in `Guile` in the search bar
3. Install the extension, then reload VSCode (Ctrl+R)

## Build

```sh
yarn install
npx js-yaml syntaxes/guile.tmLanguage.yaml > syntaxes/guile.tmLanguage.json
npx vsce package
```

## Release Notes

See [here](CHANGELOG.md).
