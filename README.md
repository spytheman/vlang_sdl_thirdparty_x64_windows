# vlang_sdl_thirdparty_x64_windows
Convenience archive of all thirdparty/SDL2* folders for x64 windows, for vlang/sdl .

This repository creates enough libraries that after cloning it locally with:
`git clone https://github.com/spytheman/vlang_sdl_thirdparty_x64_windows ~/.vmodules/sdl/thirdparty`

then `./v -os windows ~/.vmodules/sdl/examples/tvintris/` successfully cross compiles the game on Ubuntu 20.04 .

To run it, you need to also copy some .dll files, right next to the produced executable:
```sh
cp ~/.vmodules/sdl/thirdparty/dlls/x64/*.dll ~/.vmodules/sdl/examples/tvintris/
```
