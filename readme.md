# Rust 學習

https://rust-lang.tw/book-tw/title-page.html

## 在 Linux 或 macOS 上安裝 rustup

```sh
# 安裝
curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh

source "$HOME/.cargo/env"

# MacOS,C編譯器
xcode-select --install

# Ubuntu,GCC或Clang
sudo apt install build-essential

# 查看版本
rustc --version
```
