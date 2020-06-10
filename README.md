Err Repro:

```
asdf reshim # if using asdf
sudo apt-get install -y gcc-mingw-w64 mingw-w64
rustup target add x86_64-pc-windows-gnu
cargo build --release --target x86_64-pc-windows-gnu
```
