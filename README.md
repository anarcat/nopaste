# nopaste

An Emacs package to send buffer contents to [App::Nopaste](http://github.com/sartak/app-nopaste).

Should be installed by hand until this is [added to MELPA](https://github.com/melpa/melpa/pull/5601).

## Usage

Example usage with a custom path and nick:

    (require 'nopaste)
    (setq nopaste-nick "avar")

The recommended keybindings are:

    (global-set-key (kbd "C-c n p") 'nopaste)
    (global-set-key (kbd "C-c n y") 'nopaste-yank-url)

Requires Emacs 25 or later and the `nopaste` command.

## Similar projects

 * [debpaste.el](https://github.com/alezost/debpaste.el) talks only to https://paste.debian.org/
 * [pastebinit](https://launchpad.net/pastebinit/) another command similar to `nopaste`, not yet supported by `nopaste.el`
