Hacking
====

This repository contains the source code that comes from the book: Hacking The Art of Exploitation, 2nd edition.

## Notes
The VM that this code runs on is an Ubuntu-based Live Linux Distro.  It contains all of the source
code and the code all compiles under GCC version 3.3.6.  

It's also worth noting that much of the exploits won't work under GCC 4 with the buffer overflow
detection.  Instead of stack-smashing and moving on, it will detect buffer overflows and seg fault
without overflowing the buffers.  (Using the VM lets you play with the exploits).


## Related Links
* get the live linux disc: [downlooad here](https://www.dropbox.com/s/eho0p2q8oaz53h1/hacking-live-1.0.iso?dl=0)
* http://www.amazon.com/Hacking-The-Art-Exploitation-Edition/dp/1593271441 - buy your own copy of the book
* For a more comprehensive introduction to gdb, check out the Using GNU's GDB Debugger tutorial by Peter Jay Salzman, available at [link](https://web.archive.org/web/20150221100621/http://www.dirac.org/linux/gdb/00-Administrata.php#whywritethistutorial).
