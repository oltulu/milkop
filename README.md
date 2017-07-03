![Snapshot](https://github.com/oltulu/milkop/blob/master/milkopana.png)
# Easy Program Installer (EPI)
EPI is a program for installing most used programs by users easily after a fresh boot of a new os.
It has been written in C++ & Qt-5, so you can compile the program yourself if you have Qt-Creator.

# How to install EPI?
### You can download .mps.lz file from here: (Easy & Fast)


### You can compile from source code:
Just open .pro folder with QtCreator

But it you have to compile from source code [yaml-cpp](https://github.com/jbeder/yaml-cpp) library first.
```
git clone https://github.com/jbeder/yaml-cpp.git
cd yaml-cpp
mkdir build
cd build
make yaml-cpp_directory_here
cmake
```
Done.
