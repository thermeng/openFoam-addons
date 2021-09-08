# OpenFOAM-addons
Tips &amp; tricks for an openfoam user

## Requirement 
1. Windows Subsystem for Linux 2 (WSL2)
2. Any Text Editor - VIM Prefered
3. Remote Desktop Connection app

## Steps
1. Open *.bashrc* file
2. Add following lines to the end of your *.bashrc* file 
```
sudo systemctl enable dbus && sudo /etc/init.d/dbus start && sudo /etc/init.d/xrdp start
```
3. Save & exit
