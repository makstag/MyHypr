# MyHypr fedora
enable right mouse click  
```sh
gsettings set org.gnome.desktop.peripherals.touchpad click-method 'areas'
sudo dnf -y update
```

install hyprland  
```sh
sudo dnf copr enable solopasha/hyprland
sudo dnf install -y hyprland
```

install dependencies  
```sh
sudo dnf install -y xdg-desktop-portal-hyprland hyprwayland-scanner hyprpaper waybar dolphin hyprlock nm-applet
```  

clone config  
```sh
git clone --depth=1 https://github.com/makstag/MyHypr.git ~/.config
```  

check devices  
```sh
hyprctl devices
```
