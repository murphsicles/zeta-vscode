# Zeta Language Support for VS Code

Syntax highlighting, snippets, and language support for the [Zeta programming language](https://github.com/murphsicles/zeta).

## Features

- **Syntax Highlighting** — Full TextMate grammar with scoped highlighting for:
  - Keywords, types, and operators
  - Strings (double-quoted, single-quoted, raw)
  - Numbers (binary, hex, float, integer)
  - Comments (line, block, documentation)
  - Function declarations, variable declarations
  - Attributes, preprocessor directives
  - Module/path syntax

- **Code Snippets** — Handy snippets to speed up your Zeta coding:
  - `fn` — Function declaration
  - `let` / `letmut` — Variable declarations
  - `if` / `while` / `for` / `match` — Control flow
  - `struct` / `enum` / `impl` — Type definitions
  - `main` / `pubfn` / `asyncfn` — Function templates
  - `println` — Print line
  - `mod` / `use` — Module declarations
  - `test` — Test function

- **Language Configuration** — Auto-closing pairs, bracket matching, comment toggling, indentation rules

## Installation

### From VS Code Marketplace (when published)

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X`)
3. Search for "Zeta Language Support"
4. Click Install

### From VSIX

1. Download the `.vsix` from [Releases](https://github.com/murphsicles/zeta-vscode/releases)
2. In VS Code, go to View → Command Palette (`Ctrl+Shift+P`)
3. Run "Extensions: Install from VSIX..."
4. Select the downloaded file

### From source

```bash
git clone https://github.com/murphsicles/zeta-vscode.git
cd zeta-vscode
npm install -g @vscode/vsce
vsce package
code --install-extension zeta-vscode-*.vsix
```

## File extensions

- `.z` — Zeta source files
- `.zeta` — Zeta source files (alternative)

## License

MIT
