# Installing NvChad Version 2.5
## Backup and remove old nvim config.
Backup old nvim config.
```
mv ~/.config/nvim ~/.config/nvim-old
```
Or remove old nvim config.
```
rm -rf ~/.config/nvim
```
Remove local/state and local/share
```
rm -rf ~/.local/state/nvim
rm -rf ~/.local/share/nvim
```
## Install NvChad.
Install required packages archllinux.
```
sudo pacman -S --needed unzip luarocks xclip wl-clipboard
```
Install required packages parrot.
```
sudo apt install unzip luarocks xclip wl-clipboard
```

Install NvChad config from https://nvchad.com/docs/quickstart/install
```
git clone https://github.com/NvChad/starter ~/.config/nvim && nvim
```
Or this already configured version
```
git clone https://github.com/haxorg-ux/nvstarter ~/.config/nvim && nvim
```
