# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system:
* git
* stow

## Installation

First, check out the dotfiles repo in your $HOME directory using git
``` bash
cd ~/
git clone git@github.com/inemesisi/dotfiles.git .dotfiles
```

then use GNU stow to create symlinks
``` bash
cd .dotfiles
stow .
cd ..
```
