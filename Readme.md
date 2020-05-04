# Aggregated PIR for creating a corona heatmap

This repository contains the source code of the paper [1] by researchers of TU Graz. For more information on the project, visit https://covid-heatmap.iaik.tugraz.at/.

### Source code
The code is based on Microsoft SEAL (https://github.com/Microsoft/SEAL) and is compatible with Windows and Linux.
This repository contains a demo application to perform the matrix multiplication on encrypted data and to compute the challenge masks. Use `params.h` for a parametrization of the code.

### Compilation:
Execute the following commands to compile the source code:
```
bash ./install_seal.sh
mkdir build
cd build
cmake ..
make
```

[1] not yet public