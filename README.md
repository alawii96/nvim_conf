1. Get Neovim
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
./nvim.appimage --appimage-extract
./squashfs-root/AppRun --version

sudo mv squashfs-root /
sudo ln -s /squashfs-root/AppRun /usr/bin/nvim
nvim

2. Get NvChad
git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim

3. Clone this repository and replace files if needed


Supported languages :
1. Rust
2. Lua

