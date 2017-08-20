# AVnPy

This is an alternative version of [vnpy/vnpy](https://github.com/vnpy/vnpy). It is entirely for personal purpose. If you like the changes I made, it would be great!

## Target:

1. Port to Python3.
2. Port to Qt5 for QtChart pkg.
3. x64 support for all components.
4. Remove the dependence to Anaconda as it doesn't support QtChart yet.
5. Write code for hist data importing


Instructions for compiling ta-lib x64:
1. Download and Upzip ta-lib-0.4.0-msvc.zip
2. Move the Unzipped folder ta-lib to C:\
3. Dowdload and install Visual Studio Community 2017 (Remember to select [Visual C++] feature)
4. Build ta-lib Library
    1) From Windows Start Menu, Start [VS2017 x64 Native Tools Command Prompt]
    2) Move to c:\ta-lib\c\make\cdr\win32\msvc
    3) Build the library <code>nmake</code>
5. Then <code>pip3 install ta-lib</code>