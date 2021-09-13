# tinyfugue
TinyFugue is a text-based, line-based client designed for connecting to most flavors of MU* servers (TinyMUSH, TinyMUX, LP, Diku, etc.) or any telnet-based chatserver. 

## Build Instructions
It's your standard download/configure/make/make install routine. Regarding configure options, this is what I recommend (YMMV, obviously):

```
./configure \
        --enable-atcp \
        --enable-gmcp \
        --enable-option102
```
