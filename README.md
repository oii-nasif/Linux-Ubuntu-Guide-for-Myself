### Software Installation 
1. **Google Chrome**
    * Download the chrome debian file ( [Google Chrome Download](updatethelink) )
```sh
sudo dpkg -i google-chrome-stable_current_amd64.deb
```
2. **Pycharm Professional**
```sh
sudo snap install pycharm-professional --classic
```
3. **Install Codecs and Microsoft Fonts**
```sh
sudo apt install ubuntu-restricted-extras
```

### Problems Installation
1. **Solve Dependency Problem**
    * installation command before and after this command
```sh
sudo apt -f install
```

### Different Setups
1. **Minimize the Dock**
```sh
gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'focus-minimize-or-previews'
```

2. **Download Bengali Fonts**
    * [Omicronlab Bengali Fonts](https://www.omicronlab.com/bangla-fonts.html)
