# Voidrice (My personal dotfiles)
These are the dotfiles deployed for MARBS.
This is a highly opinionated dotfile setup. Please make modifications before installing or using.

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- emacs (text editor)
	- zsh (shell)
	- sxhkd (general key binder)
	- lf (file manager)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- tmux
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/files`
	- Directory bookmarks in `~/.config/directories`

## Usage
These dotfiles are intended to go with emacs and other programs I use:

- [ratpoison](http://www.nongnu.org/ratpoison/) (window manager)
- [st](https://github.com/lukesmithxyz/st) (Luke Smiths's fork of ST)

## Install these dotfiles and all dependencies
Use MARBS (my other repo) to autoinstall everything:

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/konstantine-v/MARBS/blob/master/progs.csv).

## Please Note
These haven't been tested since about 2021-2022 so please make changes on another machine before going in and using it on a personal machine

## Picture of you
![Alt text](.local/share/larbs/larbs.png)