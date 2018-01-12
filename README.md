aleph1ow dotfiles
===============

Inspired by [kennyadsl](https://github.com/kennyadsl/dotfiles).

Requirements
------------

Set zsh as your login shell.

    chsh -s /bin/zsh

Install [rcm](https://github.com/mike-burns/rcm).

    brew tap thoughtbot/formulae
    brew install rcm

Install
-------

Clone onto your home:

    git clone git://github.com/aleph1ow/dotfiles.git

Rename it to `.dotfiles`

Install:

    env RCRC=$HOME/.dotfiles/rcrc rcup

This will create symlinks for config files in your home directory.

You can safely run `rcup` multiple times to update.

What's in it?
-------------

pure prompt theme
