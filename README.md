# dotfiles

```
paru -S awesome-git picom-git zsh redshift thunar kitty ranger neovim htop rofi zip unzip p7zip xclip lightdm lightdm-gtk-greeter gvfs neofetch pavucontrol ttf-ms-win11-auto nerd-fonts-jetbrains-mono noto-fonts noto-fonts-cjk networkmanager lxappearance materia-gtk-theme papirus-icon-theme lsd mpd
```

```
git clone --recursive https://github.com/mariod8/dotfiles
cd dotfiles
sh install.sh
```

```
sudo systemctl enable --now NetworkManager
sudo systemctl enable --now mpd
sudo systemctl enable lightdm
```