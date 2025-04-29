# corrade - C++11 multiplatform utility library

This is a `build2` package repository for [`corrade`](https://github.com/mosra/corrade),
a C++11 multiplatform utility library.

This file contains setup instructions and other details that are more
appropriate for development rather than consumption. If you want to use
`corrade` in your `build2`-based project, then instead see the
`PACKAGE-README.md` file accompanying each package.

The development setup for `corrade` uses the standard `bdep`-based workflow.
For example:

```
git clone .../corrade.git
cd corrade

bdep init -C @gcc cc config.cxx=g++
bdep update
bdep test
```
