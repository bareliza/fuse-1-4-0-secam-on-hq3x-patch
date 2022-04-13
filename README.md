# fuse-1-4-0-secam-on-hq3x-patch

This patch gives you SECAM color TV feeling on fuse zx spectrum emulator,
that is scanlines plus "out of synchronization" effect. 
Level of synchronzsation can be set up by F11 and F12 keys.

Locate files from directory 'updated' in fuse-1.4.0 and replace them.
'updated1' dir has new keymapping - Alt+F11, Alt+F12 secam sync,
F11 - 100% emulation speed, F12 - 10000% emulation speed

then type

    ./configure --with-sdl
    ./make
   
Currently works only with sdl configuration.
Works with 1.4.0 version, also with 1.5.7 version of fuse.
