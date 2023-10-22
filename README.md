#rustos
Following [Writing an OS in Rust](https://os.phil-opp.com/).

## Installation

In your home directory,

```shell
cargo install bootimage
cargo component add llvm-tools-preview
```

In project directory,

```shell
rustup component add rust-src
cargo bootimage
```

## How to run

```shell
cargo run
```
