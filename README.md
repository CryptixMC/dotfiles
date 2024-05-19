# dotfiles by cryptix
## installation
### git
```
sudo pacman -S git
```
### yay
```
git clone https://aur.archlinux.org/yay-bin
cd yay-bin
makepkg -si
```
### Required Packages
```
yay -S chezmoi hyprland hyprpaper neovim waybar
```
## setup
```
chezmoi init --apply CryptixMC
```
