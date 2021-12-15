# plang-mode
Emacs major mode for https://p-org.github.io/P/

# Issues

1. Indentation has issues with things like `if` statement one-liners that don't use braces.
2. Indentation in general is iffy.
3. ???? - you tell me!

# Using with Doom Emacs

In your `~/.doom.d/` directory, make these changes:

## packages.el
```elisp
(package! plang-mode
  :recipe (:host github :repo "wnka/plang-mode"
          :files ("plang-mode.el")))
```


## config.el

```elisp
(use-package! plang-mode)
```
