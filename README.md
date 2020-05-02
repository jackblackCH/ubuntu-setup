# Ubuntu Setup for Frontend Engineers
A step by step guide to setup Ubuntu for Frontend Software Engineers (coming from macOS)

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

sudo apt install zsh
sudo apt-get install powerline fonts-powerline

# Install an initial version of nodejs. We use the lts version of node. After a node version is installed, you probably work with a node version manager.
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt install nodejs
```

## Install Apps 
You probably should use "snap" which is the new software hub of these freaks
Use `snap find "media player"` to find software

```
sudo snap install code --classic
sudo snap install slack --classic
sudo snap install telegram-desktop
```

## Settings, Shell & Configs
```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"

git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```

## Resources
https://github.com/romkatv/powerlevel10k#oh-my-zsh
