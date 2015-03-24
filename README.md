Unicornleap
===========

A reimplementaion of KevinLiddle/unicornleap using CoreAnimation. Forked from jgdavey/unicornleap.

Added in a troll face to allow for either a unicorn or a troll face jumping across the screen.

Installation
------------

### "Automatic" installation

    make
    make install

The default installation prefix is /usr/local. You can change it with
the PREFIX env variable.

### Manual installation

1. `make`
2.  Copy the binary from `build` folder to somewhere in your path
3.  Create 2 images at `~/.unicornleap/unicorn.png` and `~/.unicornleap/sparkle.png`


Usage
-----

Unicorn:
    unicornleap
    
Troll Face:
    unicornleap -t
