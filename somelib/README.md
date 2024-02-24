# somelib - A C++ library

The `somelib` C++ library provides <SUMMARY-OF-FUNCTIONALITY>.


## Usage

To start using `somelib` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: somelib ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = somelib%lib{<TARGET>}
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
[bool] config.somelib.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
