# Ubuntu Setup for Frontend Engineers
A step by step guide to setup Ubuntu for Frontend Software Engineers (coming from macOS)

Version: Ubuntu 18.04.4 LTS (bionic)

## SSH keys
```
ssh-keygen
```
[Add to GitHub](https://github.com/settings/keys)

## Install tools
```
sudo apt install curl
sudo apt install git
sudo add-apt-repository universe
sudo apt install gnome-tweak-tool
sudo apt install neofetch

sudo apt install zsh
sudo apt install powerline fonts-powerline

# Install an initial version of nodejs (12.x.x lts). 
# You probably install a node version manager via npm from now on.

curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt install nodejs
```

## Install Apps 
You probably should use "snap" which is the new software hub of these freaks
Use `snap find "media player"` to find software

```
sudo snap install chromium
sudo snap install code --classic
sudo snap install slack --classic
sudo snap install telegram-desktop
```

## Settings, Shell & Configs
```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"

# Powerline (Shell colors and tweaks)
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k

# TODO: Install and activate all dotfiles and configs from github
```

## Teaks
### Reduce Overheating
```
sudo add-apt-repository ppa:linrunner/tlp
sudo apt-get update
sudo apt-get install tlp tlp-rdw
sudo tlp start
```

## Resources
https://www.ubuntupit.com/how-to-speed-up-ubuntu-linux-must-follow-tips/
https://github.com/romkatv/powerlevel10k#oh-my-zsh

### Tweaks and configs
https://gist.github.com/pinge/dedf6511cd5459bf8e13
