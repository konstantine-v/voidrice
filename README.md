# The Voidrice (MaterialFuture's dotfiles)
These are the dotfiles deployed for MARBS.

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
Use [MARBS](https://) to autoinstall everything:

```
curl -LO https://raw.githubusercontent.com/MaterialFuture/MARBS/master/marbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/MaterialFuture/MARBS/blob/master/progs.csv).
