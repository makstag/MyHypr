# MyHypr fedora  
Monitor 1920x1080  
<div align="center">
    <img src="monitor1.png" style="margin: auto"/>
</div>  

Monitor 3440x1440  
<div align="center">
    <img src="monitor2.png" style="margin: auto"/>
</div>  

enable right mouse click  
```sh
gsettings set org.gnome.desktop.peripherals.touchpad click-method 'areas'
sudo dnf -y update
```

install hyprland  
```sh
sudo dnf copr enable solopasha/hyprland -y
sudo dnf install -y hyprland
```

install dependencies  
```sh
sudo dnf install -y xdg-desktop-portal-hyprland hyprwayland-scanner hyprpaper waybar dolphin hyprlock nm-applet hyprcursor hyprshot
```  

clone config  
```sh
git clone --depth=1 https://github.com/makstag/MyHypr.git ~/.config
```  

check devices  
```sh
hyprctl devices
```
# Useful  
https://wiki.hyprland.org/FAQ  
