# czech-holidays

This package adds [Czech](https://en.wikipedia.org/wiki/Czech_Republic) holidays to the Emacs calendar.

If you have `org-agenda-include-diary` set to `t`, these will be also listed in the `org-agenda` view.

# Installation

This package is available on MELPA, just `M-x` `package-install` `czech-holidays`. If you want to install it manually, clone this repository somewhere, add it to `load-path`, and do `(require 'czech-holidays)`.

# Configuration

Add a call to `(czech-holidays-add)` somewhere in your `.emacs`. Note that this must be called *before* Emacs calendar is loaded.
