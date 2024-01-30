# vscode-ohm

[Ohm language](https://github.com/ohmjs/ohm) support for Visual Studio Code (VSCode). Currently provides syntax highlighting only. Rather strict, enforces each `RuleBody` to be written on one line, starting with `|`. However, this limitation provides for great formatting!

## Manual installation

1. Clone this repository
2. Run `npm i` to install dependencies
3. Run `npm run vsce pack` to bundle extension in `.vsix` format
4. Use `Extensions: Install from VSIX` command in your VSCode and point it to the newly bundled extension

## Samples

* `samples/tact-grammar.ohm` is taken from [tact-lang/tact](https://github.com/tact-lang/tact/blob/main/src/grammar/grammar.ohm) under MIT license
* `samples/ohm-grammar.ohm` with slight modifications is taken from [ohmjs/ohm](https://github.com/ohmjs/ohm/blob/main/packages/ohm-js/src/ohm-grammar.ohm) under MIT license

## License

[MIT](LICENSE)
