# Installation

```
sudo apt update -y
sudo apt install git -y
sudo apt install stow -y
cd ~
git clone git@github.com:Mantellumius/dotfiles.git
mkdir dotfiles
cd dotfiles
stow --adopt .
```