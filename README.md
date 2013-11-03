sunny-day-theme
===============

emacs24 theme with a light yellow background

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("marmalade" . "http://marmalade-repo.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))

    (package-initialize)



This will add the gnu, marmalade and melpa repos to your emacs setup.

To install the theme

**M-x package-install** sunny-day-theme


To use the sunny-day theme when starting emacs, add this to your init.el:

    (load-theme 'sunny-day)


