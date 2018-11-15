# flymake-vnu

A [v. NU HTML checker](https://validator.github.io/validator/) flymake backend.

# Installation

Ensure that you have java installed and download the [NU HTML checker](https://github.com/validator/validator/releases/). Then, customize the `flymake-vnu-jar` variable to the location of the downloaded vnu.jar file.

## Usage

``` emacs-lisp

(require 'flymake-vnu)

(with-eval-after-load 'flymake
  (flymake-vnu-setup))

```

