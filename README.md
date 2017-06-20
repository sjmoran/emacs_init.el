# emacs_init.el
Configuration file for my personal emacs programming environment

This Emacs environment configuration file enables a rich Python programming IDE. I tend to favoura lightweight and fast Emacs environment in my day-to-day programming work (rather than a more feature rich IDE such as PyCharm).
I've setup my Emacs environment according to the init.el file featured in this repository. The following packages are used:

* Emacs material theme: https://github.com/cpaulik/emacs-material-theme
* Elpy: the Emacs Lisp Python environment https://github.com/jorgenschaefer/elpy
* Flycheck: syntax checking http://www.flycheck.org/en/latest/
* Pylint: for code analysis (coding standards, error detection) https://www.pylint.org/
* Ropemacs: python refactorings and code-assists https://github.com/python-rope/ropemacs
* Pymacs: allows both-way communication between Emacs Lisp and Python https://github.com/pinard/Pymacs

My configuration is largely built on the excellent blog article from Jess Hamrick: http://www.jesshamrick.com/2012/09/18/emacs-as-a-python-ide, with changes to the configuration here and there to adapt it to my own tastes and requirements. 

To use this configuration in your own work, simply copy this file into ~/.emacs.d/. Then create the following directories with associated libraries within the ~/.emacs.d/ folder:

* fill-column-indicator-1.83/  
  * install https://github.com/alpaker/Fill-Column-Indicator
* python-mode-6.0.11/ 
  * install https://launchpad.net/python-mode
* ropemacs-0.7/ 
  * install https://github.com/python-rope/ropemacs
* pymacs-0.25/ 
  * install https://github.com/pinard/Pymacs
* highlight-current-line-0.57/ 
  * https://www.emacswiki.org/emacs/highlight-current-line.el

This configuration has been tested on Centos/Redhat. Any feedback welcome!