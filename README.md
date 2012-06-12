buffer-tail.el
==============

keeps focus on the bottom of a given buffer

written by elbeardmorez
copied from stackoverflow (http://stackoverflow.com/a/6341139/10771)

## install

install by putting it in your load path, and doing a `(require 'buffer-tail)` in your init.el

## usage
provides the `toggle-buffer-tail` function to toggle the tailling of a buffer
can force it to "on" or "off"

```scheme
(toggle-buffer-tail "foo.log")
```
