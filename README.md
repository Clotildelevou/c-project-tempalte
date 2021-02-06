# Project structure template in C

## Usage
Using [CMake](https://cmake.org/) for compilation

Using [CTest](https://cmake.org/cmake/help/latest/manual/ctest.1.html) for unit testing

Using Python for functional testing

Using [pre-commit](https://pre-commit.com/) and [clang-format](https://clang.llvm.org/docs/ClangFormat.html) for style

## Project's tree
The project's tree must look like this:
```bash
.
├── CMakeLists.txt
├── conftest.py
├── includes
├── README.md
├── src
│   └── main.c
└── tests
    ├── functional_tests    
    └── unit_tests
```
