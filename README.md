# Merustmar Language Support

**Merustmar** is a Visual Studio Code extension that provides syntax highlighting and basic language support for the **Merustmar** programming language (`.mrm` files).

![VS Code Extension](https://img.shields.io/badge/VS%20Code-Extension-blue.svg)
![Version](https://img.shields.io/badge/version-0.0.1-green.svg)

## Features

This extension enriches your development experience in VS Code with the following features:

- **Syntax Highlighting:** Clear colorization for keywords, strings, numbers, and built-in functions.
- **Bracket Matching:** Automatic highlighting of matching brackets `[]`, `{}`, and `()`.
- **Auto-Closing Pairs:** Automatically closes brackets and quotes as you type.
- **Comment Toggling:** Support for `//` line comments.

## Supported Language Elements

The extension currently highlights the following elements:

- **Keywords:** Control flow and declaration keywords.
- **Built-in Functions:** Support for standard library functions like `len`, `first`, `last`, `push`, `print_at`, `terminal_init`, etc.
- **Strings:** Double-quoted strings with escape character support.
- **Numbers:** Integers and floating-point numbers.
- **Booleans:** `true` and `false` constants.

## Installation

### From VS Code Marketplace
*(Available once published)*
1. Open Visual Studio Code.
2. Go to the Extensions view (Ctrl+Shift+X).
3. Search for `Merustmar`.
4. Click **Install**.

### Manual Installation (from .vsix)
1. Download the `.vsix` file from the releases.
2. Open VS Code.
3. Open the Command Palette (Ctrl+Shift+P).
4. Type `Extensions: Install from VSIX...` and select the downloaded file.

## Usage
Open any file with the `.mrm` extension, and VS Code will automatically activate the syntax highlighting.

## Release Notes

### 0.0.1
- Initial release of Merustmar extension.
- Basic syntax highlighting for `.mrm` files.
- Added language configuration for comments and brackets.

## Known Issues

None at this time. If you find a bug, please open an issue on the GitHub repository.

## Contributing

Contributions are welcome! Feel free to submit pull requests to improve syntax patterns or add new features.

**Enjoy coding in Merustmar!**
```

