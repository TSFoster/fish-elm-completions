# Note: This package is for Elm v0.18 only. For Elm 0.19 completions, see [TSFoster/fish-elm-completion](https://github.com/TSFoster/fish-elm-completion)

# Elm completions for `fish`

## Features

Full completions for `elm-make`, `elm-package` (including all available package names), `elm-reactor`, `elm-repl` and `elm-test`.

![](elm-suggestions.gif)

A couple of example journeys in text:

```fish
> elm-pa[TAB] # elm-package
> elm-package i[TAB] # elm-package install
> elm-package install ev[TAB] # elm-package install evancz/
> elm-package install evancz/[TAB]
[suggestions] evancz/elm-graphics evancz/elm-markdown ...
```

```fish
> elm-rea[TAB] # elm-reactor
> elm-reactor --a[RIGHT ARROW] # elm-reactor --address
> elm-reactor --address=[RIGHT ARROW] # elm-reactor --address=0.0.0.0
```

## Installation

**NOTE:** You need `curl` installed for the interactive package completions.

### [Fisherman](https://github.com/fisherman/fisherman)

```fish
> fisher ohanhi/fish-elm-completions
```

### Curl

```sh
$ curl -L https://raw.githubusercontent.com/ohanhi/fish-elm-completions/master/hooks/install.fish | fish
```
