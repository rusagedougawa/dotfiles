dotfiles
=========

## Installation

```bash
mkdir -p ~/git/rusagedougawa/dotfiles

git clone https://github.com/rusagedougawa/dotfiles ~/git/rusagedougawa/dotfiles

ln -s ~/git/rusagedougawa/dotfiles/.zshenv ~/.zshenv
ln -s ~/git/rusagedougawa/dotfiles/.zsh.d ~/.zsh.d
ln -s ~/git/rusagedougawa/dotfiles/.vimrc ~/.vimrc
ln -s ~/git/rusagedougawa/dotfiles/.editorconfig ~/.editorconfig

chsh -s `which zsh` ${USER}
```

## Requirements
- git
- zsh
- vim
