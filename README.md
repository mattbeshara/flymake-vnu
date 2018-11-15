# flymake-vnu

A Flymake handler for html files using the [v. NU HTML checker](https://validator.github.io/validator/)

# Installation

First ensure that you have java installed and [download the NU HTML checker](https://github.com/validator/validator/releases/). After loading the flymake-vnu extension customize the flymake-vnu-jar variable to point to downloaded vnu.jar file.

## Usage

``` emacs-lisp

(require 'flymake-vnu)

(with-eval-after-load 'flymake
  (flymake-vnu-setup))

```

