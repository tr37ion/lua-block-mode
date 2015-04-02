# lua-block.el - highlight matching block

Based on ruby-block.el by khiker

Copyright (C) 2010 by meegee
Copyright (C) 2007-2009  khiker

Author: khiker <khiker.mail+elisp@gmail.com>
Maintaner: meegee <themgzzy gmail com>

Keywords languages, faces, lua

## License
This file is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2, or (at your option)
any later version.

This file is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with GNU Emacs; see the file COPYING.  If not, write to
the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor,
Boston, MA 02110-1301, USA.

## Commentary:
This is basically a refactored version of ruby-block.el by khiker.
Some stuff like repeat ... until statements are missing but it
works well enough.

## Usage:
Add this line to your .emacs:

    ;; Load and Enable lua-block-mode
    (require 'lua-block)
    (lua-block-mode t)

In addition, you can also add one of these too:

    ;; do overlay
    (setq lua-block-highlight-toggle 'overlay)
    ;; display to minibuffer
    (setq lua-block-highlight-toggle 'minibuffer)
    ;; display to minibuffer and do overlay
    (setq lua-block-highlight-toggle t)

Default is minibuffer and overlay.

## Tested on
Emacs 22.3.2, Emacs 23.0.95.2 and Emacs 24.0.50.1

## Note
lua-mode.el is necessary to use this package.
