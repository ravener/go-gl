# OpenGL 2.1 bindings for Go
This is my personal repository for OpenGL bindings for Go generated using [Glow](https://github.com/go-gl/glow)

I mainly use only OpenGL 2.1 so it was undesirable to depend on [go-gl](https://github.com/go-gl/gl) itself which would download all the packages nonetheless, so for smaller downloads this package contains just what I need.

This package also disables ALL extensions (i.e EXT, ARB, NV, ATI, etc. functions) aiming to be a pure OpenGL binding since I am still learning OpenGL and don't see the need for extensions yet.
