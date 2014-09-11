# Lorem Ipsum for Emacs #

Add filler lorem ipsum text to Emacs

## Installation

Soon to be added to the normal Emacs package repositories.

**Manual Installation**

Add `lorem-ipsum.el` to your `load-path`.  That's it, all the
functions you need are `autoload`ed.


## Setup

Use the default keybindings by adding the following to your .emacs
file:

    (Lorem-ipsum-use-default-bindings)


This will setup the folling keybindings:

Key Binding | Function
------------|------------------------------
`C-c l p`   | Lorem-ipsum-insert-paragraphs
`C-c l s`   | Lorem-ipsum-insert-sentences
`C-c l l`   | Lorem-ipsum-insert-list

If you want different keybinding, say you want the prefix C-c C-l, use a variation of the
following:

    (global-set-key (kbd "C-c C-l s") 'Lorem-ipsum-insert-sentences)
    (global-set-key (kbd "C-c C-l p") 'Lorem-ipsum-insert-paragraphs)
    (global-set-key (kbd "C-c C-l l") 'Lorem-ipsum-insert-list)
