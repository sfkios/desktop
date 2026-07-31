
```
sudo grubby --update-kernel=ALL --args="systemd.tpm2_wait=false"
sudo hostnamectl set-hostname fedora
sudo cp /etc/hosts /etc/hosts.bak
sudo nano /etc/hosts
sudo reboot
mkdir -p ~/.themes ~/.icons
tar -xvf ~/Downloads/Nordic-darker.tar.xz -C ~/.themes/
tar -xvf ~/Downloads/Nordic-Folders.tar.xz -C ~/.icons/
tar -xvf ~/Downloads/papirus-icon-theme-nordic-folders.tar.xz -C ~/.icons/
gtk-update-icon-cache -f -t ~/.icons/Papirus-Dark/
tar -xvf ~/Downloads/capitaine-cursors-r4.tar.gz -C ~/.icons/
mkdir -p ~/.local/share/xfce4/terminal/colorschemes
mv ~/Downloads/nord.theme ~/.local/share/xfce4/terminal/colorschemes/
sudo dnf install -y rsms-inter-fonts jetbrains-mono-fonts
```

[Wallpaper](https://unsplash.com/photos/silhouette-of-trees-covered-by-fog-KT3WlrL_bsg)
[Themes](https://www.xfce-look.org/p/1267246)
