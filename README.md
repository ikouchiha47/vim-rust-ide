# vim-rust-ide

(Inspired from vim-go-ide, copy-paste-programming, doesn't change default vim config)

- Install rust
- Install [rustup](https://www.rustup.rs/)
- Install racer and create a symlink to /usr/local/bin, `cargo install racer && ln -s <install_binary_file_location> /usr/local/bin/racer`
- After installing rustup, follow the `racer` configuring instructions [here](https://github.com/phildawes/racer#configuration)
- `git clone <url> ~/.vim_rust_runtime`
- `sh ~/.vim_rust_runtime/bin/install`

To load vim with the config `vim -u ~/.vimrc.rust`


Or make a file `vim-rust`

```
#!/usr/bin/env bash
vim -u ~/.vimrc.rust
```
Move the file to `/usr/local/bin` and  `chmod +x /usr/local/bin/vim-rust`

####Plugins used
- pathogen
- neocomplete
- NERDtree
- rust.vim
- vim-racer
- syntastic
- neo(*)
- auto-pairs
- bufexplorer
- vim-gitgutter
 
####TODO:
- Add a rustfmt on save
- Strip away not required stuff
- Make a minimal and a maximal configuration

