# vim-rust-ide

(Inspired heavily by vim-go-ide, copy-paste-programming)

- Install rust
- Install rustup
- `cargo install racer && ln -s <install_binary_file_location> /usr/local/bin/racer`
- `git clone <url> ~/.vim_rust_runtime`
- `sh ~/.vim_rust_runtime/bin/install`

To load vim with the config `vim -u ~/.vimrc.rust`

Or make a file `vim-rust`

```
#!/usr/bin/env bash
vim -u ~/.vimrc.rc
```
Move the file to `/usr/local/bin` and  `chmod +x /usr/local/bin/vim-rust`
 
TODO:
- Strip away not required stuff
- Make a minimal and a maximal configuration
