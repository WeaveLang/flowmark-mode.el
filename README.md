# flowmark-mode.el
Emacs major mode for Flowmark

## Install

Download `flowmark-mode.el` to any directory of your choice and put this in your `.emacs` file:

``` elisp
(add-to-list 'load-path 'PATH-TO-YOUR-ELISP-FILE-DIR)
(require 'flowmark-mode)
(add-to-list 'auto-mode-alist '("\\.fm\\'" . flowmark-mode))
```
