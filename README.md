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

* Check fur unused dependencies (must fix packunused [#18](https://github.com/hvr/packunused/issues/18)
* Create a Stack template out of this repo when it matures
