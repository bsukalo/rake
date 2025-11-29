# rake

<p align="center">
  <img width="553" height="479" alt="Screenshot 2025-11-29 at 12 44 08" src="https://github.com/user-attachments/assets/5c4a74bd-4156-4987-aabe-797c1198b4ca" />
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
   git clone https://github.com/yourusername/rake.git
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


## License

MIT
