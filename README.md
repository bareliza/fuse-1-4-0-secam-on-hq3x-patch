# fuse-1-4-0-secam-on-hq3x-patch

This patch gives you SECAM color TV feeling on fuse zx spectrum emulator,
that is scanlines plus "out of synchronisation" effect. 
Level of synchronisation can be set up by F11 and F12 keys.

Locate files from directory 'updated' in fuse-1.4.0 and replace them.

then type

    ./configure --with-sdl
    ./make
   
Currently works only with sdl configuration.
Not tested with other than 1.4.0 version of fuse.
