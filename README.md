# ExcelFiles

[![License][license-img]](LICENSE)
[![CI][ci-img]][ci-url]
[![codecov][codecov-img]][codecov-url]
[![dev][docs-dev-img]][docs-dev-url]
[![stable][docs-stable-img]][docs-stable-url]
[![DOI][doi-img]][doi-url]

[license-img]: http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ci-img]: https://github.com/queryverse/ExcelFiles.jl/workflows/CI/badge.svg
[ci-url]: https://github.com/queryverse/ExcelFiles.jl/actions?query=workflow%3ACI
[codecov-img]: https://img.shields.io/codecov/c/github/queryverse/ExcelFiles.jl/master.svg?label=codecov&style=flat-square
[codecov-url]: http://codecov.io/github/queryverse/ExcelFiles.jl?branch=master
[docs-dev-img]: https://img.shields.io/badge/docs-dev-blue.svg?style=flat-square
[docs-dev-url]: https://queryverse.github.io/ExcelFiles.jl/dev
[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg?style=flat-square
[docs-stable-url]: https://queryverse.github.io/ExcelFiles.jl/stable

## Overview

This package provides support for Excel files under the
[FileIO.jl](https://github.com/JuliaIO/FileIO.jl) package.

It provides functionality to read simple tabular data from 
an Excel (.xlsx) file and to save simple tabular data to an 
Excel file.

For more extensive functionality when reading and writing Excel files,
consider using [XLSX.jl](https://juliadata.github.io/XLSX.jl/stable/).

## Requirements

* Julia v1.8

* Linux, macOS or Windows

* XLSX.jl v0.11.11 or higher

## Installation

From a Julia session, run:

```julia
julia> using Pkg

julia> Pkg.add("ExcelFiles")
```

## Source Code

The source code for this package is hosted at
[https://github.com/queryverse/ExcelFiles.jl](https://github.com/queryverse/ExcelFiles.jl).

## License

The source code for the package **ExcelFiles.jl** is licensed under
the [MIT "Expat" License](https://github.com/queryverse/ExcelFiles.jl/master/LICENSE).

## Getting Help

If you're having any trouble, have any questions about this package
or want to ask for a new feature,
just open a new [issue](https://github.com/queryverse/ExcelFiles.jl/issues).

## Contributing

Contributions are always welcome!

To contribute, fork the project on [GitHub](https://github.com/queryverse/ExcelFiles.jl)
and send a Pull Request.


## Alternative Packages

* [XLSX.jl](https://github.com/juliadata/XLSX.jl)