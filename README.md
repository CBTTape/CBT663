# CBT663
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 663 is from Paul Edwards, and contains a public domain    *   FILE 663
//*           runtime C Library.                                    *   FILE 663
//*                                                                 *   FILE 663
//*                  Public Domain C runtime library                *   FILE 663
//*                  -------------------------------                *   FILE 663
//*                                                                 *   FILE 663
//*      Version : 0.73                                             *   FILE 663
//*      Released: 1998-04-07                                       *   FILE 663
//*                                                                 *   FILE 663
//*      Written by Paul Edwards.                                   *   FILE 663
//*      Released to the public domain.                             *   FILE 663
//*      You may use this entire package for any purpose            *   FILE 663
//*      whatsoever without restriction.                            *   FILE 663
//*                                                                 *   FILE 663
//*                                                                 *   FILE 663
//*                                                                 *   FILE 663
//*      INTRODUCTION                                               *   FILE 663
//*      ------------                                               *   FILE 663
//*                                                                 *   FILE 663
//*      This project is to create a public domain runtime          *   FILE 663
//*      library which conforms to ISO/IEC 9899:1990.  It is        *   FILE 663
//*      expected to be highly OS-specific, but hopefully not too   *   FILE 663
//*      compiler-specific.  It is the job of C library             *   FILE 663
//*      developers to make unportable but fast code, not that of   *   FILE 663
//*      the application developers.  Anyone wishing to             *   FILE 663
//*      contribute to this project, please contact Paul Edwards    *   FILE 663
//*      at avon@matra.com.au.                                      *   FILE 663
//*                                                                 *   FILE 663
//*                                                                 *   FILE 663
//*      MAIN DESIGN GOALS                                          *   FILE 663
//*      -----------------                                          *   FILE 663
//*                                                                 *   FILE 663
//*      1. Application developers should not have to resort to     *   FILE 663
//*         DosOpen, open et al in order to get better              *   FILE 663
//*         performance for binary files.                           *   FILE 663
//*                                                                 *   FILE 663
//*      2. Application developers should not have to resort to     *   FILE 663
//*         using binary mode to get better performance for fgets   *   FILE 663
//*         in text mode.                                           *   FILE 663
//*                                                                 *   FILE 663
//*      CURRENT STATUS                                             *   FILE 663
//*      --------------                                             *   FILE 663
//*                                                                 *   FILE 663
//*      A substantial, but still incomplete version under          *   FILE 663
//*                                                                 *   FILE 663
//*      OS/2 for:                                                  *   FILE 663
//*      EMX 0.9b                                                   *   FILE 663
//*      Watcom C++ 10.0b                                           *   FILE 663
//*      IBM CSET++ 2.0                                             *   FILE 663
//*      Borland C++ 1.5                                            *   FILE 663
//*                                                                 *   FILE 663
//*      DOS for:                                                   *   FILE 663
//*      Borland C++ 3.1                                            *   FILE 663
//*      Watcom C++ 10.0b                                           *   FILE 663
//*                                                                 *   FILE 663
//*      MVS for:                                                   *   FILE 663
//*      IBM C/370 v2r1m0                                           *   FILE 663
//*                                                                 *   FILE 663
//*      PDOS for:                                                  *   FILE 663
//*      EMX 0.9b                                                   *   FILE 663
//*                                                                 *   FILE 663
//*                                                                 *   FILE 663
//*      WHO WANTS IT?                                              *   FILE 663
//*      -------------                                              *   FILE 663
//*                                                                 *   FILE 663
//*      It is expected that this archive will interest the         *   FILE 663
//*      following groups of people:                                *   FILE 663
//*                                                                 *   FILE 663
//*      1. People who have a commercial compiler, such as CSET,    *   FILE 663
//*      but would like to have the source code to the C runtime    *   FILE 663
//*      library, so that they can have control over it.            *   FILE 663
//*                                                                 *   FILE 663
//*      2. People who have a commercial compiler, such as          *   FILE 663
//*      Borland, where although they have the runtime source,      *   FILE 663
//*      Borland have some restrictions on the use of their         *   FILE 663
//*      object code, saying that the resultant executable must     *   FILE 663
//*      have either their copyright notice on it, or yours, or     *   FILE 663
//*      some such rubbish.                                         *   FILE 663
//*                                                                 *   FILE 663
//*      3. People who have EMX 0.9b, but would like to be able     *   FILE 663
//*      to modify the runtime library code without being bound     *   FILE 663
//*      by any of EMX's licensing restrictions on doing that.      *   FILE 663
//*                                                                 *   FILE 663
//*      4. People who are interested in the internal workings of   *   FILE 663
//*      a runtime library, and would like unrestricted use of      *   FILE 663
//*      any useful code they may find whilst investigating that.   *   FILE 663
//*                                                                 *   FILE 663
//*      5. Someone who wants to write their own commercial C       *   FILE 663
//*      compiler and library, and wants something to use as a      *   FILE 663
//*      base.  This at least gives you the library, there are no   *   FILE 663
//*      public domain C compilers available to the best of my      *   FILE 663
//*      knowledge, on any platform.                                *   FILE 663
//*                                                                 *   FILE 663
//*      6. People who have ISO text-processing programs that       *   FILE 663
//*      want a significant speed improvement.                      *   FILE 663
//*                                                                 *   FILE 663
//*      USAGE                                                      *   FILE 663
//*      -----                                                      *   FILE 663
//*                                                                 *   FILE 663
//*      There are makefiles for all the different compilers        *   FILE 663
//*      supported.  Choose the one you want, and compile it,       *   FILE 663
//*      creating a library if you want, and then compiling your    *   FILE 663
//*      programs in the same way that the "pdptest" program is     *   FILE 663
//*      compiled.                                                  *   FILE 663
//*                                                                 *   FILE 663
```
