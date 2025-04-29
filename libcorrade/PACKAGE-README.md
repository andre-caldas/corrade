# libcorrade - A C++ library

This is a `build2` package for the [`Corrade`](https://magnum.graphics/corrade/)
C++ library. It provides a multiplatform utility library written in C++11/C++14.
It’s used as a base for the Magnum graphics engine, amongother things.


## Usage

To start using `libcorrade` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: libcorrade ^2025.04.29
```

Then import the library in your `buildfile`:

```
import libs = libcorrade%lib{corrade}
```


## Importable targets

This package provides the following importable targets:

```
lib{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libcorrade.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
