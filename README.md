# vscode-cel

[![CI](https://github.com/hmarr/vscode-cel/actions/workflows/ci.yml/badge.svg)](https://github.com/hmarr/vscode-cel/actions/workflows/ci.yml)
<a href="https://marketplace.visualstudio.com/items?itemName=hmarr.cel"><img src="https://img.shields.io/visual-studio-marketplace/v/hmarr.cel?label=vscode%20marketplace&color=blue&logo=visual-studio-code" /></a>

Adds syntax highlighting for [CEL (Common Expression Language)](https://opensource.google/projects/cel) to Visual Studio Code.

<p align="center">
  <img alt="CEL syntax highlighting" src="https://raw.githubusercontent.com/hmarr/vscode-cel/main/images/cel-syntax-highlighting.png" width="433px">
</p>

Install it from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=hmarr.cel).

## Developing

Clone the project, and open up in vscode. Start a debugging session (just press F5) to launch a new window with the plugin loaded, and hack away.

You might find it helpful to copy the contents of [examples.cel](examples/examples.cel) into the editor window while you're working on the plugin to get live feedback.

The project includes a [test suite](syntaxes/tests) (using the wonderful [vscode-tmgrammar-test](https://github.com/PanAeon/vscode-tmgrammar-test)). To run the tests, it's `npm test`. If you run the "Run grammar tests" task in vscode, you'll get failure annotations in the test files if something's not working. If you're contributing any improvements or fixes, I'd be grateful if you could include a test. Fortunately vscode-tmgrammar-test makes them pretty easy to write.
