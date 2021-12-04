# aoc-2021

My solutions for [Advent of Code 2021](https://adventofcode.com/).

In [SBCL](http://www.sbcl.org/) or [CCL](https://clozure.com/), `(load "<file>")` to run one of the solutions.

E.g. `(load "~/lisp/aoc-2021/day01")`

Or, from the shell:

```
$ cd .../aoc-2021
$ sbcl --script day01.lisp
or
$ ccl --load day01.lisp
```

day04.lisp requires that the file `"~/quicklisp/setup.lisp"` exists.

If that isn't already the case on your system, since `sbcl` doesn't natively load from a URL, as CCL does, if you're using that, you'll need to download [beta.quicklisp.org/quicklisp.lisp](http://beta.quicklisp.org/quicklisp.lisp), load it, and run `(quicklisp:quickstart:install)`.


