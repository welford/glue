# glue

This webpage generates a header and source file from the glcorearb.h/glext.h/wglext.h files. These generated files can be used in a win32 project to enable pointers to the OpenGL functions that Windows does not support by default.


## How to use

Drag and drop:

1. glcorearb.h OR glext.h
2. wglext.h 

Into this webpage and it will generate a gl.h and gl.c file for you to download, which you can include in your project to enable gl extension.

You can drag and drop either the files themselves or the raw text from the file. Both will work.

Links to the generated files will then be generated which you can download. This works on Chrome but not currently on Edge.
