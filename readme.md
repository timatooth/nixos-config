```
sudo mv /etc/nixos /etc/nixos.bak
sudo git clone https://github.com/timatooth/nixos-config /etc/nixos
sudo cp /etc/nixos.bak/hardware-configuration.nix /etc/nixos/
sudo ln -sr /etc/nixos/machines/$MACHINE.nix /etc/nixos/configuration.nix
```
