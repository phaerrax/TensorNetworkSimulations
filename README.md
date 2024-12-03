# TensorNetworkSimulations

This is a personal Julia registry, containing some packages of mine related to the world of numerical simulations of quantum systems.

* [`TEDOPA`](https://github.com/phaerrax/TEDOPA.jl) provides functions to compute the chain-mapping of continuous quantum systems (see e.g. [1] and [2]).
* [`LindbladVectorizedTensors`](https://github.com/phaerrax/LindbladVectorizedTensors.jl) extends [`ITensor`](https://github.com/ITensor/ITensors.jl)'s collection of site types to work with density matrices instead of just pure states.
* [`MarkovianClosure`](https://github.com/phaerrax/MarkovianClosure.jl) implements the Markovian closure construction as seen in [3] and [4].
* [`PauliStringTensors`](https://github.com/phaerrax/PauliStringTensors.jl) provides some small utilities to read and print Pauli strings, and to convert them into `ITensor` objects.
* [`QuantumCircuitSimulator`](https://github.com/phaerrax/QuantumCircuitSimulator.jl) is a generic simulator of quantum circuits with matrix-product states (still a work in progress).

## Installation

To add this registry, run from an interactive session

```julia
using Pkg
pkg"registry add https://github.com/phaerrax/TensorNetworkSimulations.git"
```

This must be done just once per Julia installation; once this is done, you can install any of the packages in this registry with `]add <packagename>` as you would with any package in Julia's `General` registry, without having to use the GitHub repository URL.

## References

1. J. Prior, A. W. Chin, S. F. Huelga, and M. B. Plenio, [Phys. Rev. Lett. 105, 050404 (2010)](https://doi.org/https://doi.org/10.1103/PhysRevLett.105.050404)
2. D. Tamascelli, A. Smirne, J. Lim, S. F. Huelga, and M. B. Plenio, [Phys. Rev. Lett 123, 090402 (2019)](https://doi.org/https://doi.org/10.1103/PhysRevLett.123.090402)
3. A. Nüßeler, D. Tamascelli, A. Smirne, J. Lim, S. F. Huelga, and M. B. Plenio, [Phys. Rev. Lett. 129, 140604 (2022)](https://doi.org/10.1103/PhysRevLett.129.140604)
4. D. Ferracin, A. Smirne, S. F. Huelga, M. B. Plenio and D. Tamascelli, [J. Chem. Phys. 161, 174114 (2024)](https://doi.org/10.1063/5.0226723)
