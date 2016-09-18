# Yasnippet unofficial snippet collections

[![Join the chat at https://gitter.im/AndreaCrotti/yasnippet-snippets](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/AndreaCrotti/yasnippet-snippets?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
This repository contains custom snippets for [yasnippet](http://github.com/capitaomorte/yasnippet) If you want to get the official snippets, please check out this repository: https://github.com/AndreaCrotti/yasnippet-snippets

# How to install

If you want to use this custom snippets collection proceed as follows:

1. clone this repository
2. add to your .emacs the following
   - `(add-to-list 'yas-snippet-dirs "$$DIRECTORY_WHERE_YOU_CLONED")`
   - and in case you want to enable yasnippet globally: `(yas-global-mode t)`

3. `M-x yas-reload-all` to activate them

# Contributing

If you have any useful snippets for any language or framework please feel free to contribute.

To study the current snippets I suggest to use `M-x yas-describe-tables`
which will gave a table representation of all the snippets available in the current mode.


# Guidelines

Snippets need to be generic enough to be useful for everyone, and not contain anything specific to your own system.

# Various notes

## HTML snippets

Until September 1st 2014 there were a lot of HTML snippets in the repository, which were sometimes useful but I came to the conclusion that yasnippet was not the right fool for them, so they were removed in this pull request:
https://github.com/AndreaCrotti/yasnippet-snippets/pull/49

To everyone writing a lot of HTML I suggest using [emmet mode](https://github.com/smihica/emmet-mode) instead, which is a much more powerful mode for writing HTML tags.
