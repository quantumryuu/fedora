# Fedora Customization

## Extensions
- [Alphabetical App Grid ](https://extensions.gnome.org/extension/4269/alphabetical-app-grid/ )
- [Appindicator Support ](https://extensions.gnome.org/extension/615/appindicator-support/ )
- [Background Logo ](https://extensions.gnome.org/extension/7364/background-logo/ )
- [Blur My Shell ](https://extensions.gnome.org/extension/3193/blur-my-shell/ )
- [Brightness Control Using Ddcutil ](https://extensions.gnome.org/extension/2645/brightness-control-using-ddcutil/ )
- [Bring Out Submenu Of Power Offlogout Button ](https://extensions.gnome.org/extension/2917/bring-out-submenu-of-power-offlogout-button/ )
- [Dash To Dock ](https://extensions.gnome.org/extension/307/dash-to-dock/ )
- [Gnome 40 Ui Improvements ](https://extensions.gnome.org/extension/4158/gnome-40-ui-improvements/ )
- [Impatience ](https://extensions.gnome.org/extension/277/impatience/ )
- [Just Perfection ](https://extensions.gnome.org/extension/3843/just-perfection/ )
- [Launch New Instance ](https://extensions.gnome.org/extension/600/launch-new-instance/ )
- [No Overview ](https://extensions.gnome.org/extension/4099/no-overview/ )
- [Quick Settings Audio Panel ](https://extensions.gnome.org/extension/5940/quick-settings-audio-panel/ )
- [Solaar Extension ](https://extensions.gnome.org/extension/6162/solaar-extension/ )
- [User Themes ](https://extensions.gnome.org/extension/19/user-themes/ )
- [Weather Oclock ](https://extensions.gnome.org/extension/5470/weather-oclock/ )
- [Tiling Shell ](https://extensions.gnome.org/extension/7065/tiling-shell/ )
- [Hide Top Bar ](https://extensions.gnome.org/extension/545/hide-top-bar/ )
- [Disable Unredirect Fullscreen Windows ](https://extensions.gnome.org/extension/1873/disable-unredirect-fullscreen-windows/ )

## Wallpaper
[Download](https://wallpapercave.com/download/abstract-sphere-hd-wallpapers-wp7268793])

## Fonts
`sudo dnf install curl cabextract xorg-x11-font-utils fontconfig`

`sudo rpm -i https://downloads.sourceforge.net/project/mscorefonts2/rpms/msttcore-fonts-installer-2.6-1.noarch.rpm`

`sudo fc-cache -v`

## Nvidia Drivers + Secure Boot
`sudo dnf install kmodtool akmods mokutil openssl`

`sudo kmodgenca -a`

`sudo mokutil --import /etc/pki/akmods/certs/public_key.der`

`systemctl reboot`

`sudo dnf update -y`

`sudo dnf install akmod-nvidia`

`sudo dnf install xorg-x11-drv-nvidia-cuda`

## DDCUTIL
[Instructions](https://github.com/daitj/gnome-display-brightness-ddcutil?tab=readme-ov-file#setup-ddcutil)
