# Learn Yew!
This is React like Rust framework

# Install

## Install WebAssembly target
```
rustup target add wasm32-unknown-unknown
```
## Install Trunk
```
# note that this might take a while to install because it compiles everything from scratch
# Trunk also provides prebuilt binaries for a number of major package managers
# See https://trunkrs.dev/#install for further details
cargo install --locked trunk
cargo install wasm-pack
```