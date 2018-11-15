# flymake-vnu

A [v. NU HTML checker](https://validator.github.io/validator/) flymake backend.

# Installation

First ensure that you have java installed and [download the NU HTML checker](https://github.com/validator/validator/releases/).



## Usage

``` emacs-lisp

(require 'flymake-vnu)

(with-eval-after-load 'flymake
  (flymake-vnu-setup))

```

