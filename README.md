# weave-mode.el
Emacs major mode for Weave

## Install

Download `weave-mode.el` to any directory of your choice and put this in your `.emacs` file:

``` elisp
(add-to-list 'load-path 'PATH-TO-YOUR-ELISP-FILE-DIR)
(require 'weave-mode)
(add-to-list 'auto-mode-alist '("\\.w\\'" . weave-mode))
```
