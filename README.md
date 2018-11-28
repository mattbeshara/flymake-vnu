[![MELPA](https://melpa.org/packages/flymake-vnu-badge.svg)](https://melpa.org/#/flymake-vnu)

# flymake-vnu

A [v. NU HTML checker](https://validator.github.io/validator/) flymake backend.



# Installation

Ensure that you have java installed and download the [NU HTML checker](https://github.com/validator/validator/releases/). Then, customize the `flymake-vnu-jar` variable to the location of the downloaded vnu.jar file.


## After loading flymake-vnu manually

``` emacs-lisp

(require 'flymake-vnu)

(with-eval-after-load 'flymake
  (flymake-vnu-setup))

```

## Using use-package and MELPA

``` emacs-lisp

(use-package flymake-vnu
  :ensure t
  :config
  (flymake-vnu-setup))

```
