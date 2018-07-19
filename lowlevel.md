# LOW LEVEL

## Memory

What every programmer should know about memory
http://futuretech.blinkenlights.nl/misc/cpumemory.pdf

Memory & Caches (1h11)
https://www.youtube.com/watch?v=4_smHyqgDTU

Understanding Strict Aliasing
https://cellperformance.beyond3d.com/articles/2006/06/understanding-strict-aliasing.html

Handles are the better pointer
https://floooh.github.io/2018/06/17/handles-vs-pointers.html

### Alignemnt

Data alignment : Straighten up and fly right
https://www.ibm.com/developerworks/library/pa-dalign/

The Lost Art of C Structure Packing
http://www.catb.org/esr/structure-packing/

### Load / Hit Store

## SIMD

SIMD at Insomniac Games
http://www.gdcvault.com/play/1022249/SIMD-at-Insomniac-Games-How 

## Optimization

Optimization Manuals
http://agner.org/optimize/#manuals

## Assembly

Assembly is too high-level (45min)
https://www.youtube.com/watch?v=eunYrrcxXfw

Programming from the Ground Up
https://savannah.nongnu.org/projects/pgubook/

x86-64 Assembly Language Programming with Ubuntu
http://www.egr.unlv.edu/~ed/assembly64.pdf

Assembly Language for Beginners
https://yurichev.com/writings/AL4B-EN.pdf

## Computer architecture

Building an 8-bit breadboard computer (Youtube Playlist)
https://www.youtube.com/watch?v=HyznrdDSSGM&list=PLowKtXNTBypGqImE405J2565dvjafglHU

## Linking libraries in far too many ways

* Static Lib Linking (.lib)
* Dynamic Lib Linking (.dll)
* Implicit Linking (load-time)
* Name Import Library
* Explicit Linking (run-time)
* ABI (put ABI reference for Unix)
* Linking with asm and C
* Static functions (no function table by the linker)
* Why chose static over dynamic ?
* Why chose implicit over explicit ?
* What about other OS ? (Linux, consoles)
* Code examples (obviously)
* .def files on Window
* function name mangling in C++ ...


### Websites / ref
https://msdn.microsoft.com/en-us/library/windows/desktop/ms681914.aspx (lots of other ref at the end)
https://www.youtube.com/watch?v=JPQWQfDhICA (Everything you ever wanted to know about DLLs)
http://www.cs-fundamentals.com/tech-interview/c/difference-between-static-and-dynamic-linking.php (static vs dynamic linking)
https://stackoverflow.com/questions/1993390/static-linking-vs-dynamic-linking
https://msdn.microsoft.com/en-us/library/7k30y2k5.aspx (how to export a function in Windows)
See how handmade hero does it (even for linux : -fPIC -shared)
See the Handmade Hero episode where he explains the map that you can look at in Windows
https://msdn.microsoft.com/en-us/library/zxk0tw93.aspx
https://msdn.microsoft.com/en-us/library/3y1sfaz2.aspx
Some stackoverflow :
https://stackoverflow.com/questions/6251171/architecturally-what-is-the-difference-between-a-shared-object-so-and-a-dynami
https://stackoverflow.com/questions/538134/exporting-functions-from-a-dll-with-dllexport
https://stackoverflow.com/questions/2538103/how-to-call-a-function-from-a-shared-library
