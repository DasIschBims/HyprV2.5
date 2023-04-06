# HyprV2.5
A fork of an improved hyprland deployment script. Now with Nvidia support!

### Table of Contents
- [HyprV2.5](#hyprv25)
    + [Table of Contents](#table-of-contents)
    + [About](#about)
    + [Installation](#installation)
    + [Packages](#packages)

### About
Modified version of the Hyprland install script from [SolDoesTech](https://github.com/SolDoesTech/) for running my own personal setup with a few tweaks such as more packages, my dotfiles and Nvidia fixes.
This script is meant to be run on a fresh installation of Arch Linux.

### Installation
>:warning: I am not responsible for any damage this script could cause! Be warned.

If you're running this make sure to install the following packages first:
- git
- yay
- nvidia-dkms

Make sure to follow the [Hyprland wiki](https://wiki.hyprland.org/Nvidia/) for the rest of the setup before running this script.

Then run the following commands to install Hyprland using this script:
```bash
git clone https://github.com/DasIschBims/HyprV2.5.git
cd HyprV2.5
chmod +x ./set-hypr
./set-hypr
```

---

### Packages

Below is a list of the packages that would be installed:

| Package Name                    | Description                                                                                     |
|---------------------------------|-------------------------------------------------------------------------------------------------|
| hyprland-bin                    | This is the Hyprland compositor                                                                 |
| hyprpaper-git                   | This is a wallpaper manager for Hyprland                                                        |
| alacritty                       | This is my terminal emulator of choice                                                          |
| waybar-hyprland                 | This is a fork of waybar with Hyprland workspace support                                        |
| swaylock-effects                | This allows for the locking of the desktop its a fork that adds some additional visual effects  |
| wofi                            | This is an application launcher menu                                                            |
| wlogout                         | This is a logout menu that allows for shutdown, reboot and sleep                                |
| mako                            | This is a graphical notification daemon                                                         |
| xdg-desktop-portal-hyprland-git | xdg-desktop-portal backend for hyprland                                                         |
| grim                            | This is a screenshot tool it grabs images from a Wayland compositor                             |
| slurp                           | This helps with screenshots, it selects a region in a Wayland compositor                        |
| thunar                          | This is a graphical file manager                                                                |
| polkit-gnome                    | needed to get superuser access on some graphical applications                                   |
| python-requests                 | needed for the weather module script to execute                                                 |
| pamixer                         | This helps with audio settings such as volume                                                   |
| pavucontrol                     | GUI for managing audio and audio devices                                                        |
| network-manager-applet          | Applet for managing network connection                                                          |
| gvfs                            | adds missing functionality to thunar such as automount usb drives                               |
| thunar-archive-plugin           | Provides a frontend for thunar to work with compressed files                                    |
| file-roller                     | Backend set of tools for working with compressed files                                          |
| btop                            | Resource monitor that shows usage and stats for processor, memory, disks, network and processes |
| noto-fonts                      | fonts needed by the weather script in the top bar and other applications                        |
| lxappearance                    | used to set GTK theme                                                                           |
| xfce4-settings                  | set of tools for xfce, needed to set GTK theme                                                  |
| sddm-git                        | development version of SDDM which is a display manager for graphical login                      |
| sddm-sugar-candy-git            | an sddm theme                                                                                   |
| ttf-firacode-nerd               | Nerd fonts for icons and overall look                                                           |
| neofetch                        | Fetching...                                                                                     |
| pfetch-git                      | My fetching tool of choice                                                                      |
| xdg-user-dirs                   | For creating user dirs and setting env vars                                                     |
| playerctl                       | Audio settings                                                                                  |


### Hyprland Fixes (Nvidia)

| Package Name            | Description |
|-------------------------|-------------|
| nvidia-vaapi-driver-git | ---         |
| libva-git               | ---         |
| qt5ct                   | ---         |
| qt5-wayland             | ---         |

