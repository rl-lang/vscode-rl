# rl-lang - VS Code Syntax Highlighting

Syntax highlighting for [rl-lang](https://github.com/rl-lang/rl-lang), a statically typed interpreted language built in Rust.

## Features

- Syntax highlighting for .rl files
- Keywords, operators, literals, strings, and comments
- Based on TextMate grammar so it works with any theme

## Usage

Install the extension and open any .rl file. Highlighting is applied automatically.

If VS Code doesn't detect the language, select RL from the language picker in the bottom status bar.

## Example

dec int x = 10
dec string name = "rl-lang"

fn greet(string name) {
    println("Hello, ", name)
}

greet(name)
## Related

- [vscode-rl-lsp](https://github.com/rl-lang/vscode-rl-lsp) - diagnostics and hover via the rl language server
- [vscode-rl-lang](https://github.com/rl-lang/vscode-rl-lang) - run, check, and scaffold projects from the editor

## Links

- Language: [rl-lang/rl-lang](https://github.com/rl-lang/rl-lang)
- Extension: [rl-lang/vscode-rl](https://github.com/rl-lang/vscode-rl)

## License

MIT
