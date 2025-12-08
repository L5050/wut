

# wut
A fork of WUT that can create custom RPL files for color splash modding.

Licensed under the terms of the zlib License (see [LICENSE.txt](LICENSE.txt)).

## Install
First, install [devkitPro and devkitPPC](https://devkitpro.org/wiki/Getting_Started), then follow the building from source instructions below

### Building wut projects with CMake
You can easily build any devkitPro CMake based wut project with the following commands:
```
mkdir build && cd build
/opt/devkitpro/portlibs/wiiu/bin/powerpc-eabi-cmake ../
make
```

## Building from source

Building wut is simple as running the following commands:
```
make
(sudo -E) make install
```
