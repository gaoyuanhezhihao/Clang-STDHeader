Suppose you are using clangd with compile_flags.txt.

And there is std::pmr::vector in your code,

Clangd will failed to analysis this code, since std::pmr has not been supported in newest clang++ (2022.2.8).

This repo added std::pmr to vector, list header files.


