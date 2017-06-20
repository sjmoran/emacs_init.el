# emacs_init.el
Configuration file for my emacs programming environment

This Emacs environment configuration file enables a rich Python programming IDE. Given that I am generally allergic to more heavyweight IDEs such as Pycharm, I tend to favour Emacs in my day-to-day programming work.
I've setup my Emacs according to the init.el featured in this repository. The following packages are used:

* Emacs material theme: https://github.com/cpaulik/emacs-material-theme
* Elpy: the Emacs Lisp Python environment https://github.com/jorgenschaefer/elpy
* Flycheck: syntax checking http://www.flycheck.org/en/latest/
* Pylint: for code analysis (coding standards, error detection).
* Ropemacs: python refactorings and code-assists https://github.com/python-rope/ropemacs
* Pymacs: allows both-way communication between Emacs Lisp and Python https://github.com/pinard/Pymacs

My configuration is largely built on the excellent blog article from Jess Hamrick: http://www.jesshamrick.com/2012/09/18/emacs-as-a-python-ide, with changes to the configuration here and there to adapt it to my own tastes and requirements. 

To use this configuration in your own work, copy this file into ~/.emacs.d/. Then create the following directories within ~/.emacs.d/:

* fill-column-indicator-1.83
* python-mode-6.0.11
* ropemacs-0.7
* pymacs-0.25
* highlight-current-line-0.57

Any feedback welcome!