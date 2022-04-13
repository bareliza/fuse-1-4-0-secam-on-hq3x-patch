# fuse-1-4-0-secam-on-hq3x-patch

This patch gives you SECAM color TV feeling on fuse zx spectrum emulator,
that is scanlines plus "out of synchronization" effect. 
Level of synchronization can be set up by F11 and F12 keys.

Locate files from directory 'updated' in fuse-1.4.0 and replace them.

then type

    ./configure --with-sdl
    ./make
   
Currently works only with sdl configuration.
Works with 1.4.0 version, also with 1.5.7 version of fuse.
