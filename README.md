#Project structure template in C

#Usage
Using Cmake for compilation
Using CTest for unit testing
Using python for functional testing
Using pre-commit and clang-format for style

#Project's tree
The project's tree must look like this:
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
