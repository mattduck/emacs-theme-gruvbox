NO LONGER SUPPORTED BY ME! Sadly I've started using an old computer of mine that can't really keep up with Emacs all that well, making it uncomfortable for me to use it.

What I mean by that is that I can still accept pull requests and such but adding stuff myself is a little tough right now...

---

# Gruvbox theme for Emacs

Gruvbox is a retro groove color scheme for Emacs. This is a port of the Vim version originally by [Pavel Pertsev](https://github.com/morhetz) found [here](https://github.com/morhetz/gruvbox).

Another version of this theme can be found here, by Lee Machin: https://github.com/leemachin/emacs-gruvbox-theme


## Supports

This theme contains custom support for the following features and plugins:

- `whitespace-mode`
- [RainbowDelimiters](http://www.emacswiki.org/emacs/RainbowDelimiters)
- [Smartparens](https://github.com/Fuco1/smartparens)
- [ElScreen](https://github.com/knu/elscreen)

## Installation and usage

1. Download `gruvbox-theme.el`, and put it in `~/.emacs.d/themes`. For example:
   ```shell
   curl https://raw.github.com/Greduan/emacs-theme-gruvbox/master/gruvbox-theme.el > ~/.emacs.d/themes/gruvbox-theme.el
   ```

1. Tell Emacs where to find themes in your `init.el` or `.emacs` file:
   ```lisp
   (add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
   ```

1. Enable the theme:
   ```
   M-x load-theme RET gruvbox
   ```
   Or add the following to your `init.el` or `.emacs` file to load the theme at startup:
   ```
   (load-theme 'gruvbox t)
   ```

## Known bugs

None. For now...


## To-do

Nothing to do... :neutral_face:

If you want for the theme to support something please open a new issue and I'll try my best to make it work out. :smile:


## License

```
The MIT License (MIT)

Copyright (c) 2013 Lee Machin, Eduán Lávaque

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
