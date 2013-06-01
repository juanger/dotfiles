# .files

My personal dotfiles stored in the simplest way possible and custom-tailored for my environment:

* OSX
* ruby 2.0
* TextMate 2
* Git
* Brew
* rbenv
* texlive
* oh-my-zsh

Feel free to fork it for your own needs. This is intended to be a very simple dotfile repo, the only extra file is a ruby command to install all your dotfiles as symlinks in your home directory.

### Install

To run the installer you need ruby and the thor gem.

gem install thor
cd && git clone git@github.com:juanger/dotfiles.git .files
./.files/run install


