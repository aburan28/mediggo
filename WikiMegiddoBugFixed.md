Bug fixed in Megiddo library

# Introduction #

Minor bug and platform/compiler-dependent bug are now fixed in release 0.2.2.
Comparison of unsigned char arrays was making the decrypt\_para.c program behaving weird with the strcmp function for some environments and compilers. The replacement with the function strncmp makes now the code work well under any environment.