# VectorNav Firmware Library

To use this library in your git repo:
1. Add this repo as a [submodule](https://github.com/blog/2104-working-with-submodules):
```
git submodule add https://github.com/nolanholden/vectornav-firmware vectornav-firmware
```

2. Provide your the source directories in your makefile:
```
./vectornav-firmware/FWLib/library/inc # for header files
./vectornav-firmware/FWLib/library/src # for implementation files
```
