
```
sudo grubby --update-kernel=ALL --args="systemd.tpm2_wait=false"
sudo hostnamectl set-hostname fedora
sudo cp /etc/hosts /etc/hosts.bak
sudo nano /etc/hosts
sudo reboot
```
