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

Clone onto your laptop:

    git clone git://github.com/aleph1ow/dotfiles.git

Install:

    env RCRC=$HOME/dotfiles/rcrc rcup

This will create symlinks for config files in your home directory.

You can safely run `rcup` multiple times to update.

What's in it?
-------------

[vim](http://www.vim.org/) configuration:

* [gocode](https://github.com/nsf/gocode), an autocompletion daemon for the Go
  programming language.
* Syntax highlighting plugin for Go.
* Compiler plugin for Go.
* Indentation plugin for Go.
* Documentation plugin for Go.
* [Emmet.vim](https://github.com/mattn/emmet-vim) for expanding CSS selectors
  into HTML when writing markup
* Syntax highlighting for Scala.
* [vim-mkdir](https://github.com/pbrisbin/vim-mkdir) for automatically creating
  non-existing directories before writing the buffer.

[git](http://git-scm.com/) configuration:

* `l` alias for tight, colored, log output.
* My name and email.

[zsh](http://zsh.sourceforge.net/FAQ/zshfaq01.html) configuration and aliases:

* `todo` to edit my todo file, located at `~/Dropbox/todo`.
