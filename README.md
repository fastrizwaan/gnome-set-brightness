# gnome-set-brightness
Set brightness for gnome using custom shortcuts Ctrl+Alt+Super+0-9

This works both the laptops and regular LED/LCD monitors. Created because gnome 43 does not have soft brightness, and other extensions do not work with desktop monitors.

Bash scripts:
1. set-brightness (sets brightness using gsettings)
2. create-custom-shortcuts.sh (add keybindings in custom, beware, it will overwrite existing ones.)

### Install
```
git clone https://github.com/fastrizwaan/gnome-set-brightness.git
cd gnome-set-brightness
sudo bash -c "sh ./install.sh"
sh create-custom-shortcuts.sh
```

### Usage:

10 keys are assigned, press
```
Ctrl+Alt+Super+1 to 10% Brightness
Ctrl+Alt+Super+2 to 20% Brightness
Ctrl+Alt+Super+3 to 30% Brightness
Ctrl+Alt+Super+4 to 40% Brightness
Ctrl+Alt+Super+5 to 50% Brightness
Ctrl+Alt+Super+6 to 60% Brightness
Ctrl+Alt+Super+7 to 70% Brightness
Ctrl+Alt+Super+8 to 80% Brightness
Ctrl+Alt+Super+9 to 90% Brightness
Ctrl+Alt+Super+0 to 100% Brightness
```
### Copyright
(C) GPLv3 Mohammed Asif Ali Rizvan 
