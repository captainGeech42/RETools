# RETools
Random tools I made or otherwise just use for reversing quickly.

# PEDMPExtractor
* Search for PE files in a raw dump and display arch + pe file size to allow manual carving quickly

# REClass
* Live memory C, C++, and other structure rebuilding tool

# demumble
* C++ library with python wrapper to demangle Itanium and MSVC symbols on all platforms (Linux, Mac, Windows)
  * Modified from: https://github.com/nico/demumble

# JITCall 
* Command line application to JIT compile a calling stub around N number of dll exports with arguments provided the calling convention. Additionally can load shellcode or manual mapping of dlls to easily debug dllmain and can read binary files to pass arbitrary data as argument. Wait for execution by key press or int3.

# BlobRunner
* Allocate and run shellcode, print shellcode base and wait for execution by key press.

# IdaScripts
Python helper scripts to do random stuff. May contain wrappers around ida operations, binja operations, or misc python utilities useful in low level stuff.