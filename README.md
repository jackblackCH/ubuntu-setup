# Ubuntu Setup for Frontend Engineers
A step by step guide to setup Ubuntu for Frontend Software Engineers (coming from macOS)

## Install tools
```
sudo apt-get install curl
sudo apt install git
sudo add-apt-repository universe
sudo apt install gnome-tweak-tool

# Install the lts version of node (adapt version if needed)
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install nodejs
```

## Install Apps 
You probably should use "snap" which is the new software hub
```
sudo snap install code --classic
sudo snap install slack --classic
sudo snap install telegram-desktop
```

## Find Software
`snap find "media player"`

## Settings & Config
```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
```

