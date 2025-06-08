# Kilo-rs

A modern implementation of the [kilo](https://github.com/antirez/kilo) text editor in Rust. This project maintains the philosophy of being minimal and understandable while adding modern features and leveraging Rust's safety guarantees.

## Features

### Core Features (Implemented)
- Terminal-based text editing
- Raw mode terminal handling
- Basic cursor movement
- Screen refresh and rendering

### Planned Features
- Multiple buffers/tabs support
- Undo/redo functionality
- Line numbers
- Unicode support
- Syntax highlighting for multiple languages
- Auto-indentation
- Bracket matching
- Code folding
- Auto-completion
- Directory browser
- Git integration
- Split views
- Mouse support
- Configuration file support
- True color support

## Building

```bash
cargo build --release
```

## Usage

```bash
kilo-rs [filename]
```

### Key Bindings

- `Ctrl-Q`: Quit
- More keybindings coming soon...

## Design Philosophy

Like the original kilo editor, this implementation aims to be:
1. Minimal yet functional
2. Easy to understand and modify
3. Self-contained with minimal dependencies

However, we extend this philosophy by:
1. Leveraging Rust's safety guarantees
2. Supporting modern terminal features
3. Adding quality-of-life improvements
4. Maintaining extensibility without complexity

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the BSD license - see the LICENSE file for details.

## Acknowledgments

- Original kilo editor by Salvatore Sanfilippo (antirez)
- Rust community and crate authors
