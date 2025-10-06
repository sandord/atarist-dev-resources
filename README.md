# Atari 16/32 bit Development Resources

A collection of resources for developing software for the 16/32 bit Atari series of computers.

## Community Websites

- [AtariAge](https://www.atariage.com)
- [AtariCrypt](https://ataricrypt.blogspot.com)
- [Atariforum](https://atari-forum.com)
  - A forum dedicated to Atari ST development and discussions.
- [AtariAge Forums](https://forums.atariage.com)
- [Atari Mania](https://www.atarimania.com)
- [atariscne.org](https://atariscne.org)
- [D-Bug](http://d-bug.mooo.com)
- [Exxos Forum](https://www.exxosforum.co.uk/forum)
  - A forum focused on Atari ST hardware and software development.

## Books and references
- Atari ST Platform
  - [Atari Document Archive](https://docs.dev-docs.org)
  - [The Atari Compendium](https://info-coach.fr/atari/software/_development/Atari-Compendium.pdf)
    - Probably the most extensive technical reference ever published for the Atari ST and derivatives.
  - [The Atari Wiki](https://www.atari-wiki.com)
  - [The Documentation for TOS](https://freemint.github.io/tos.hyp/en/index.html)
    - The famous `tos.hyp` pages.
- Compilers
  - [GCC online documentation](https://gcc.gnu.org/onlinedocs)
- Hardware intrinsics
  - [ST/STE Scanlines](https://www.atari-wiki.com/?title=ST_STE_Scanlines)
    - This page provides pseudocode descriptions of various processes involved in the generation of each frame of the video output, in both the Atari ST and the STE.

## Blogs, wikis, and other resources

- [Beyond Brown](http://beyondbrown.d-bug.me)
- [BUS ERROR Atari 16/32 Bit Development Info Page](https://bus-error.nokturnal.pl/Welcome%2Bto%2BAtari%2Bcoding%2Bwiki%2521)
  - Has some very useful information about cross compilation and assembly, hardware reference materials and tools.
- [DrCoolZic Atari ST Site](https://info-coach.fr/atari/index.php)
  - Contains a lot of detailed information about the hardware and software side of the Atari ST.

## Discord Servers

- [Atari FreeMiNT User Group](https://discord.gg/5yZC4NwCr9)
- [Atari Scene/Demoscene](https://discord.gg/7Qn5qtsbrm)
- [Atari ST 16/32bit](https://discord.gg/qwEeYQc5jt)
- [GFABASIC](https://discord.gg/AYEwQY3JcA)

## Emulators

- [Hatari](https://www.hatari-emu.org)
  - [Hatari User manual](https://www.hatari-emu.org/doc/manual.html)
  - [Hatari Debugger manual](https://www.hatari-emu.org/doc/debugger.html)
- [STeem](https://sourceforge.net/projects/steemsse)

## C Programming

C is the primary programming language used for professional Atari ST development.

- [Makefile tutorial](https://makefiletutorial.com)
  - A very useful guide to writing Makefiles.
- [Object Oriented Programming in C](https://www.state-machine.com/oop)
  - Explains how to implement object-oriented programming concepts in C.
  - The references at the bottom of the page are also very useful.

## Assembly Programming

- [Bugaboo usage](http://beyondbrown.d-bug.me/post/bugaboo)
  - Some very interesting and useful Bugaboo debugger tips and tricks.
- [Cycle counting in the Atari ST](https://pasti.fxatari.com/68kdocs/AtariSTCycleCounting.html)
- [M68000 Programmer's Reference Manual](https://www.nxp.com/docs/en/reference-manual/M68000PRM.pdf)

## Cross compilation

This section contains resources for cross-compiling Atari ST software from other platforms. Developing on the Atari ST itself is often limited by its hardware capabilities and with cross-compilation, you can leverage more powerful development environments.

- [M68k LVVM documentation](https://m680x0.github.io/doc)
  - Resources for users of M68k LLVM toolchain.
- [Platform Guide: Atari ST](https://bumbershootsoft.wordpress.com/platform-guide-atari-st)
  - A VBCC/VASM oriented guide.
- [Thorsten Otto's m68k-atari-mint cross-tools page](https://tho-otto.de/crossmint.php)
  - A page full of resources for cross-compiling for the Atari ST using GCC.
- [VBCC](http://sun.hasenbraten.de/vbcc)
  - A highly optimizing portable and retargetable ISO C compiler.

## Github repositories

- [ReservoirGods/GODLIB](https://github.com/ReservoirGods/GODLIB)
  - An extensive C library by Resevoir Gods that provides many features that can be useful for game development.

## Tools
- [Compiler Explorer](https://godbolt.org)
  - Handy tool to see live compiler output asembly. Supports M68K GCC compilers and M68K assembly.
- [Amiga & Atari Bitmap Converter](https://github.com/arnaud-carre/abc)
  - A command line tool to convert bitmap images into ready to use binary data.
- [CycleSpitter](https://github.com/slippyex/cycleSpitter)
  - A cycle-accurate scanline splitter tool for Atari ST fullscreen (sync) programming.

## Game Development Libraries
- [Atari Game Tools](https://bitbucket.org/d_m_l/agtools)

## Game Development Articles
- [Turrican II](https://codetapper.com/atari-st/st-games/st-turrican-2) 
