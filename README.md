# Soundness Create Wallet

- Buy VPS di : [t.me/skuycloud](t.me/skuycloud)
- Trakteer buat buy Kopi : https://trakteer.id/brrrskuy/tip `<---`

# 1. Install Build Essential
```
sudo apt install build-essential pkg-config libssl-dev git-all -y
```
# 2. Install Protobuf Compiler
```
sudo apt install -y protobuf-compiler
```
# 3. Install Rust
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
source $HOME/.cargo/env
```
# 4. Install Soundness
```
soundnessup install
```
# 5. Generating Public Keys
`Change my-key to your Name`
```
soundness-cli generate-key --name my-key
```
# 6. Export Key Pharse Mnemonic
`Change my-key to your Name to see your Pharse Mnemonic`
```
soundness-cli export-key --name my-key
```
# to see guide
https://github.com/SoundnessLabs/soundness-layer/tree/main/soundness-cli

------------------

# Don't forget to save your Pharse Mnemonic
