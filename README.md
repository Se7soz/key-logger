key-logger
==========

A Linux kernel module to sniff keystrokes and saving it in an in memory buffer for further reading from /dev/klg


Features

    Sniff keyboard strokes
    Saving keyboard strokes to an in memory buffer
    The buffer is readable from /dev/klg char device
    The buffer is limited size and cyclic, so that not to consume your memory


Video demo:
    http://se7so.blogspot.com/2012/01/key-logger-kernel-space.html

Build:
    make
  
Load:
    sudo ./klg_load.sh
  
Unload:
    sudo ./klg_unload.sh

Read logs:
    cat /dev/klg
