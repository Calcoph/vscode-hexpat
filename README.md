# vscode-hexpat README

Language support for ImHex's pattern language.

## Features

Syntax hilighting.

## How to Install

There are 2 main methods.

### Option 1
1. Open the .vsix's containing folder in vscode.
2. Right click the .vsix file.
3. "Install extension".

### Option 2
`code --install-extension <extension_name>.vsix`

## Interesting token names

Some tokens will probably not be picked up by your theme,
so you should add them manually in your vscode configuration.

* `variable.language.dollar.hexpat` for the special `$` operator.
* `variable.language.parent.hexpat` for the keyword `parent`.

You can inspect all the tokens you need with vscode's `Developer: Inspect Editor Tokens and Scopes`.
