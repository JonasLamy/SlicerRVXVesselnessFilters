# 3DSlicer

This repository contains several vesselness filters binded as module for 3DSlicer

in each directory
```
mkdir build
cd build

cmake ..
make
```
This will generate an executable and associated .xml. Then install the generated slicer module by adding the bin folder to the additional modules path in Settings->Modules.

RORPO requires pybind11 submodule to compile.
```
git submodule update --init
```

## Vesselness

This repository provides 7 vesselness :

- Antiga
- Sato
- Meijering
- Jerman
- Zhang
- RORPO

The original implementation comes from : [https://github.com/JonasLamy/LiverVesselness](https://github.com/JonasLamy/LiverVesselness)
