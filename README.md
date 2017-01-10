# straight.el

> The straightforward package manager for Emacs.

This package is a work-in-progress attempt to completely replace
`package.el` and `quelpa` with a more flexible and powerful package
management system.

## Todo

* Figure out why byte-compilation doesn't seem to be working.
* Get Emacs to shut up in the echo area while building packages.
* Add a function to use `package-build` to clone a repository from a
  recipe.
* Add a function to checkout the latest versions of each package.
* Make `straight-save-versions` verify that the HEAD of each
  repository is reachable from its designated remote.
