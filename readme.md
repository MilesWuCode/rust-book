# Rust 學習

- https://rust-lang.tw/book-tw/title-page.html
- https://rustwiki.org/zh-CN/book/title-page.html

## rustup

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

# 更新
rustup update

# 解除安裝
rustup self uninstall

# 本地端技術文件
rustup doc

# 編譯
rustc main.rs
```

## cargo

```sh
# 版本
cargo --version

# 建立專案,有git
cargo new hello_cargo

# 編譯
cargo build

# 執行
cargo run

# 檢查程式碼
cargo check

# 建構發佈版本（Release）
cargo build --release
```

- 我們可以用 cargo new 產生專案。
- 我們可以用 cargo build 建構專案。
- 我們可以用 cargo run 同時建構並執行專案。
- 我們可以用 cargo check 建構專案來檢查錯誤，但不會產生執行檔。
- Cargo 會儲存建構結果在 target/debug 目錄底下，而不是放在與我們程式碼相同的目錄。
