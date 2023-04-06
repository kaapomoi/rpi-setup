# rpi-setup

# RaspberryPi dev setup

### tmux
 - https://github.com/tmux/tmux/wiki/Installing

```bash
wget https://github.com/tmux/tmux/releases/download/3.3a/tmux-3.3a.tar.gz

tar -zxf tmux-*.tar.gz
cd tmux-*/
./configure
make && sudo make install
```

### cmake
 - https://cmake.org/install/

```bash
wget https://github.com/Kitware/CMake/archive/refs/tags/v3.18.6.tar.gz
sudo apt install libssl-dev
tar -zxf v3.18.6.tar.gz
cd CMake-3.18.6/
./bootstrap
make
sudo make install
```

### neovim
 - https://github.com/neovim/neovim/wiki/Building-Neovim

```bash
git clone https://github.com/neovim/neovim
cd neovim && git checkout stable && make CMAKE_BUILD_TYPE=RelWithDebInfo
sudo make install
```



### fzf
 - https://github.com/junegunn/fzf

### vim-plug
 - https://github.com/junegunn/vim-plug

### nodejs
 - https://github.com/nodesource/distributions

### clangd
 - https://clangd.llvm.org/installation.html
