# emacs_init.el
Configuration file for my personal emacs programming environment

This Emacs environment configuration file enables a rich Python programming IDE. I tend to favour a lightweight and fast Emacs environment in my day-to-day programming and Scientific research work (rather than a more feature rich IDE such as PyCharm).
I've setup my Emacs environment according to the init.el file attached to this repository. 

The following packages are used to make coding as easy as possible:

* [Emacs material theme](https://github.com/cpaulik/emacs-material-theme) (nice and easy on the eyes!): 
* [Elpy](https://github.com/jorgenschaefer/elpy): the Emacs Lisp Python environment
* [Flycheck](http://www.flycheck.org/en/latest/): syntax checking
* [Pylint](https://www.pylint.org/): for code analysis (coding standards, error detection)
* [Ropemacs](https://github.com/python-rope/ropemacs): python refactorings and code-assists 
* [Pymacs](https://github.com/pinard/Pymacs): allows both-way communication between Emacs Lisp and Python 
* [IPython](http://ipython.org/): interactive code execution from within Emacs 
* [Interactively Do Things (ido)](https://www.emacswiki.org/emacs/InteractivelyDoThings): makes switching between buffers, opening/closing files easy
* [autopep8](friendly docstrings https://github.com/naiquevin/sphinx-doc.el): automatically formats Python code to conform to the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide
* [sphinx-doc.el](friendly docstrings https://github.com/naiquevin/sphinx-doc.el): generates [Sphinx](http://www.sphinx-doc.org/en/stable/)

My configuration is largely built on the excellent blog article from [Jess Hamrick] (http://www.jesshamrick.com/2012/09/18/emacs-as-a-python-ide), with changes to the configuration here and there to adapt it to my own tastes and requirements. 

To use this configuration in your own work, simply copy this file into ~/.emacs.d/. Then install all of the dependencies mentioned above. Having done that, the final step is to create the following directories with associated libraries within 
the ~/.emacs.d/ folder:

* fill-column-indicator-1.83/  
  * https://github.com/alpaker/Fill-Column-Indicator
* python-mode-6.0.11/ 
  * https://launchpad.net/python-mode
* ropemacs-0.7/ 
  * https://github.com/python-rope/ropemacs
* pymacs-0.25/ 
  * https://github.com/pinard/Pymacs
* highlight-current-line-0.57/ 
  * https://www.emacswiki.org/emacs/highlight-current-line.el

This configuration has currently been tested on Centos/Redhat and works as of 20th July 2017. Any feedback welcome!