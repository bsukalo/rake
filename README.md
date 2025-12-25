# rake

<p align="center">
  <img width="441" height="359" alt="rake_screenshot1" src="https://github.com/user-attachments/assets/faa982c2-5ecc-4785-96c3-2a14c21dc35f" />
  <img width="441" height="361" alt="rake_screenshot2" src="https://github.com/user-attachments/assets/7ef46246-6b69-4b40-9bda-2e2630ddb46a" />
</p>

Snake, but in the terminal.

## Building from Source

### Prerequisites

- Rust toolchain (install from [rustup.rs](https://rustup.rs))

### Dependencies

- `crossterm`
- `rand`

### Build Instructions

1. Clone the repository:
```bash
   git clone https://github.com/bnjjo/rake.git
   cd rake
```

2. Build and run:
```bash
   cargo build --release && cargo run --release
```

(Optional) Install to your PATH (note the dot at the end):
```bash
  cargo install --path .
```

or manually copy the binary:
```bash
  sudo cp target/release/rake /usr/local/bin/
```

and run!
```bash
  rake
```

### How to remove from PATH
```bash
  cargo uninstall rake
  sudo rm /usr/local/bin/rake
```

## License

MIT
