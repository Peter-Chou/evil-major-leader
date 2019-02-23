# evil-major-leader

This minor mode provides a shortcut key to reach evil-leader's mode keymap.

## Prerequisite

Make sure [evil](https://github.com/emacs-evil/evil) and [evil-leader](https://github.com/cofi/evil-leader) is installed

## Install

Put **evil-major-leader.el** into your load-path, then add following code in your init.el file.

``` emacs-lisp
(require 'evil-major-leader)
;; activate evil-major-leader-mode globally
(global-evil-major-leader-mode)
```

## Customize

customize the shortcut key:

``` emacs-lisp
;; mode key that you bind mode keymaps in evil-leader
;; by using evil-leader/set-key-for-mode function
(setq evil-major-leader-mode-key "m") 
;; customize the shortcut key ("," is the default shortcut key)
(setq evil-major-leader-default-key "\,")
```

