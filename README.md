# CSIE5437 Assignment 4 Sample Code

## Installation

[Install OpenFHE in a system directory](https://openfhe-development.readthedocs.io/en/latest/sphinx_rsts/intro/installation/linux.html)

## Download data

Download the `data.zip` file from [here](https://drive.google.com/file/d/1ycj_c1rSHvi3TVtSX_y_pdnno_TeWlfv/view?usp=sharing).

```
cd build
unzip data.zip
```

## Build

Construct Makefile.
```
cd build
cmake ..
```

Compile and generate executable. (under directory `build`)
```
make
```

## Run

Run the executable. (under directory `build`)
```
./main
```
