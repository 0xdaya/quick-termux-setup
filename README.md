# quick-termux-setup

It is a bash script which will first install most used packages and then finally turn your default bash shell into oh-my-zsh

## Usage:-

1. First you have to install ```wget```(to download the script) because the preinstalled version of ```wget``` in Termux doesn't support ssl therefore install fully featured GNU version by using ```apt install wget; hash -r``` (```hash -r``` because it clears the bash path cache so that new executables are found)

```
2. wget https://raw.githubusercontent.com/dayanandpathak/quick-termux-setup/master/pkginstall

3. chmod 700 pkginstall; ./pkginstall

```
