Simple OpenGL viewer for glTF geometry.

## Requirements

* premake4 : Requires recent `premake4` for macosx and linux, `premake5` for windows.
* GLEW
* glfw3

### MacOSX and Linux


    # optional. set pkg-config path to find glfw3
    $ export PKG_CONFIG_PATH=/path/to/pkgconfig

    > premake4 gmake
    $ make

### Windows(not tested)

    > premake5.exe vs2013
    Open .sln in Visual Studio 2013

## TODO

* [x] Texture
  * [ ] Various texture format.
* [ ] Shader
* [ ] Animation
