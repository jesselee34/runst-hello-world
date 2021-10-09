# Rust Hello World

## Blank Slate

```bash
# Install rustup (rustup is rusts system manager, think n or nvm for node)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# Executing the former command will download and install rustup, and will drop you into a command prompt

# Choose 1) Proceed with installation (default)

# this will instal `rustc` (the compiler) and `cargo` (the package manager)
```

## Install dependencies and compile
```bash
cargo build
```

## Compile and Run (dev)

```bash
cargo run
```

Compiled resources will be created under the `./target` directory

## Compile and Run (prod)

```bash
cargo run --release
```

Compiled resources will be created under the `./release` directory

## Watch mode
```bash
# The ability to watch and recompile/run is added via the cargo-watch package. It's listed in this projects deps and will be installed and compiled in the fist step from above.

cargo watch -x run
```