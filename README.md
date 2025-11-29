# rake

<p align="center">
  <img width="441" height="359" alt="Screenshot 2025-11-29 at 17 51 29" src="https://github.com/user-attachments/assets/faa982c2-5ecc-4785-96c3-2a14c21dc35f" />
</p>

Snake, but in the terminal, and written in Rust.

## Building from Source

### Prerequisites

- Rust toolchain (install from [rustup.rs](https://rustup.rs))

### Dependencies

- `crossterm`
- `rand`

### Build Instructions

1. Clone the repository:
```bash
   git clone https://github.com/bsukalo/rake.git
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
