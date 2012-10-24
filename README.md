shell-pop-el
============
shell-pop.el helps you to use shell easily on Emacs. Only one key action to work.

Installation
----------
Make sure to place shell-pop.el somewhere in the load-path and add the following lines to your .emacs file.

    (require 'shell-pop)

Customization
----------

    (shell-pop-set-universal-key (kbd "C-t"))
    (shell-pop-set-internal-mode "ansi-term")
    (shell-pop-set-internal-mode-shell "/bin/bash")
    (shell-pop-set-window-height 50)
    (shell-pop-set-window-position "bottom")
    (shell-pop-set-default-directory "/Users/kyagi/git")
    
Usage
----------
Just hit the key you bind to `shell-pop-set-universal-key'. For example, Ctrl+t above.

Screenshot
----------
![screenshot](https://raw.github.com/kyagi/shell-pop-el/master/screenshot.png)

EmacsWiki (No longer updated)
----------
http://www.emacswiki.org/emacs/ShellPop