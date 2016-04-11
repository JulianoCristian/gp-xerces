[![Build Status](https://travis-ci.org/xinzweb/gp-xerces.svg?branch=master)](https://travis-ci.org/xinzweb/gp-xerces)

# gp-xerces
Greenplum patched xerces-c in order to compile GPORCA

```
mkdir build
cd build
../configure --prefix=/usr/local
make
make install
```

# build 32-bit

```
mkdir build
cd build
CFLAGS="-m32" CXXFLAGS="-m32" ../configure --prefix=/usr/local
make
make install
```
