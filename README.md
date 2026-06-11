# rl-lang — VS Code Syntax Highlighting

Syntax highlighting for [rl-lang](https://github.com/MohamedGonem/vscode-rl), a custom programming language built in Rust.

## Features

- Syntax highlighting for `.rl` files
- Keywords, operators, literals, strings, and comments highlighted
- Based on TextMate grammar for broad theme compatibility

## Usage

Install the extension, then open any `.rl` file — highlighting is applied automatically.

If VS Code doesn't detect the language, select **RL** manually from the language picker in the status bar.

## Example

```rl
dec int x = 10
dec string name = "rl-lang"

fn greet(string name) {
    println("Hello, ", name)
}

greet(name)
```

## About rl-lang

`rl-lang` is an interpreted programming language written in Rust, featuring a lexer, parser, AST evaluator, and an interactive REPL. This extension adds editor support for writing `.rl` programs in VS Code.

- Language repository: [rl-lang](https://github.com/MohamedGonem/rl-lang)
- Extension repository: [vscode-rl](https://github.com/MohamedGonem/vscode-rl) 

## License

MIT
