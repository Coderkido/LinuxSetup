# LinuxSetup

#### Applications
git docker python-pip make curl [jq](https://stedolan.github.io/jq/)
```
sudo apt-get install git docker python-pip curl make jq
```
```
pip install setuptools
```

#### Powerline
Run `sudo bash powerlinesetup.sh`
Only works for Bash

#### VIM
Copy the .vimrc into ~/  (Need to add powerline)

---
## Aesthetics
![alt text][desktop]


#### Arc-Theme + Papirus Icons
To install [Arc](https://github.com/horst3180/arc-theme):
```
sudo apt-get install arc-theme
```

To install [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme):
```
sudo add-apt-repository ppa:papirus/papirus
sudo apt-get update
sudo apt-get install papirus-icon-theme
```
If using Gnome, open the tweak-tool and set the theme. For the shell, install the [User Themes](https://extensions.gnome.org/extension/19/user-themes/) extension. Requires [Gnome-Tweak-Tool](https://launchpad.net/ubuntu/+source/gnome-tweak-tool)

---
## Distro / Desktop specific:

#### Ubuntu + Gnome
[Gnome-Tweak-Tool](https://launchpad.net/ubuntu/+source/gnome-tweak-tool):
```
 sudo apt install gnome-tweak-tool
 ```
 [Gnome Extension Integration](https://wiki.gnome.org/Projects/GnomeShellIntegrationForChrome/Installation):
 ```
 sudo apt-get install chrome-gnome-shell
 ```
 Additionally will need to install the [firefox plugin](https://addons.mozilla.org/en-US/firefox/addon/gnome-shell-integration/)


 [desktop]: https://github.com/Coderkido/LinuxSetup/blob/master/Images/Desktop.png?raw=true "Gnome Desktop with Arc Dark"
