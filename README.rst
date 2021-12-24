


Setup
~~~~~

* PATH: default executable path (clang, cmake, make, etc...)
* LD_LIBRARY_PATH: default library path which is accessed to check for available dynamic and shared libraries (.so)
looked at when the program starts.


GCC
^^^

* LIBRARY_PATH:  default library path which is accessed to check for available static and shared libraries (.a/.so)
* CPATH: specifies a list of directories to be searched as if specified with -I, but after any paths given with -I
* C_INCLUDE_PATH: -isystem
* CPLUS_INCLUDE_PATH: -cpp-isystem


C++ Standard libraries
~~~~~~~~~~~~~~~~~~~~~~

+----------------------------------------------------------+-----------+------------------------------------------+
|                           Name                           | Acronym   |                  Licence                 |
+----------------------------------------------------------+-----------+------------------------------------------+
| GNU C++ Standard Library                                 | libstdc++ | GPLv3                                    |
+----------------------------------------------------------+-----------+------------------------------------------+
| LLVM C++ Standard Library                                | libc++    | Apache License v2.0 with LLVM Exceptions |
+----------------------------------------------------------+-----------+------------------------------------------+
| NVIDIA C++ Standard Library                              | libcu++   | Apache License v2.0 with LLVM Exceptions |
+----------------------------------------------------------+-----------+------------------------------------------+
| Microsoft C++ Standard Library                           | MSVC STL  | Apache License v2.0 with LLVM Exceptions |
+----------------------------------------------------------+-----------+------------------------------------------+
| HPX C++ Standard Library for Parallelism and Concurrency | HPX       | Boost Software License 1.0               |
+----------------------------------------------------------+-----------+------------------------------------------+
| Electronic Arts Standard Template Library                | EASTL     | BSD 3-Clause License                     |
+----------------------------------------------------------+-----------+------------------------------------------+

`See <https://en.wikipedia.org/wiki/C%2B%2B_Standard_Library>`_


C Standard libraries
~~~~~~~~~~~~~~~~~~~~

+-------------------------------+---------+-------------------+
|              Name             | Acronym |      Licence      |
+-------------------------------+---------+-------------------+
| GNU C Library                 | glibc   | LGPL-2.1-or-later |
+-------------------------------+---------+-------------------+
| musl                          | musl    | MIT License       |
+-------------------------------+---------+-------------------+
| Microsoft C run-time library  |         |                   |
+-------------------------------+---------+-------------------+

`See <https://en.wikipedia.org/wiki/C_standard_library>`_

