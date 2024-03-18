# TensorNetworkSimulations

This is a personal Julia registry, containing three packages of mine related to
the world of numerical simulations of quantum systems:

* `TEDOPA`, for the chain-mapping of continuous quantum systems
* `LindbladVectorizedTensors`, for doing calculations with density matrices of
  quantum systems as matrix product states
* `MarkovianClosure` (WIP)

## Installation

To add this registry, run from an interactive session

```julia
using Pkg
pkg"registry add https://github.com/phaerrax/TensorNetworkSimulations.git"
```

This must be done just once per Julia installation; then, install any of the
packages above with `]add <packagename>` as you would with any package in
Julia's `General` registry.
