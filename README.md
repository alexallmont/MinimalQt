# Minimal Qt build with CMake

A simple 'hello world' app for Qt as a basis for GUI projects. This builds on Win32, OSX and Linux and demonstrates automatically deploying Qt dlls next to binary.

Ensure that CMAKE_PREFIX_PATH is in your path. For example, my Visual Studio 2015 install of Qt 5.10.1 is in D:\Qt\5.10.1\msvc2015, so to set up for Windows in Git Bash:

    export PATH=/d/Qt/5.10.1/msvc2015/lib/cmake/Qt5Widgets:$PATH

Or in a standard Windows cmd.exe prompt:

    set PATH=D:\Qt\5.10.1\msvc2015\lib\cmake\Qt5Widgets;%PATH%

And then run the standard CMake setup:

    mkdir build
    cd build
    CMake ..
