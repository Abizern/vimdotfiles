## Vim dotfiles ##

This is just a basic set of customisations so that I can use Vim with others
who don't like to use Emacs.

It requires a `~/.vimrc` file containing:

    execute pathogen#infect()
    syntax on
    filetype plugin indent on

### Installation ###

Simple clone:

    git clone -o github --recursive git@github.com:Abizern/vimdotfiles.git ~/.vim

