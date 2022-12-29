## Installing Neovim

```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
./nvim.appimage
```

Expose nvim globally
```
sudo mv squashfs-root /
sudo ln -s /squashfs-root/AppRun /usr/bin/nvim
nvim
```

Create configuration file in the home directory

```
mkdir ~/.config/nvim
touch ~/.config/nvim/init.vim
```
