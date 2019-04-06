```
git clone git@github.com:iljau/libvterm-cmake.git
cd libvterm-cmake
mkdir build
```

Linux:
```
cmake -DCMAKE_INSTALL_PREFIX=./install -G "Unix Makefiles" ..
```

Windows (MSYS2):
```
cmake -DCMAKE_INSTALL_PREFIX=./install -G "MSYS Makefiles" ..
```

Build:
```
cmake --build . --target install
```
