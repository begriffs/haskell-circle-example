### High-Quality Haskell CI

[![Circle CI](https://circleci.com/gh/begriffs/haskell-circle-example.svg?style=svg)](https://circleci.com/gh/begriffs/haskell-circle-example)

Best practices for Haskell continuous integration on CircleCI. This
repo is a place to collaborate and refine techniques to enforce
clean code.

#### Features

* Uses Stack
* Draconian warning level
* HLints all files
* Checks for outdated constraints with packdeps
* Checks cabal file for possible Hackage problems
* Generates documentation coverage report
* Tests sdist packaging

#### TODO

There are more cool things we can do. See the
[issues](https://github.com/begriffs/haskell-circle-example/issues) where
I've recorded some ideas.
