# NGSIM.jl

A Julia package for working with the Next Generation Simulation dataset (NGSIM).
Was tested on the [Highway 101](http://www.fhwa.dot.gov/publications/research/operations/07030/) and [I-80](http://www.fhwa.dot.gov/publications/research/operations/06137/) datasets.

[![Build Status](https://travis-ci.org/tawheeler/NGSIM.jl.svg?branch=master)](https://travis-ci.org/tawheeler/NGSIM.jl)
[![Coverage Status](https://coveralls.io/repos/tawheeler/NGSIM.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/tawheeler/NGSIM.jl?branch=master)

This package is fully compatible with [AutomotiveDrivingModels.jl](https://github.com/sisl/AutomotiveDrivingModels.jl), providing the `Roadway` and `Trajdata` types from the NGSIM data. Roadway geometry was extracted from the NGSIM CAD files. The vehicle trajectories were filtered to provide better global positions and orientation.

The NGSIM trajectory data is available in [our first release, with instructions here](https://github.com/tawheeler/NGSIM.jl/releases).

## Git It

You just clone it! Note that you also have to clone my [Vec](https://github.com/tawheeler/Vec.jl) package.

```julia
Pkg.clone("https://github.com/tawheeler/Vec.jl.git")
Pkg.clone("https://github.com/tawheeler/Records.jl.git")
Pkg.clone("https://github.com/sisl/AutomotiveDrivingModels.jl.git")
Pkg.clone("https://github.com/tawheeler/NGSIM.jl.git")
```
Note that we do not distribute the NGSIM datasets directly (they are huge), but feel free to ping us or download the datasets yourself from their respective sites.
