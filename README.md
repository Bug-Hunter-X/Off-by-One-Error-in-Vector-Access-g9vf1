# Off-by-One Error in C++ Vector Access

This repository demonstrates a common off-by-one error when iterating through a `std::vector` in C++.  The error occurs because the loop condition `i <= vec.size()` attempts to access the element at index `vec.size()`, which is one past the last valid element (index `vec.size()-1`).

The `bug.cpp` file contains the erroneous code.  The `bugSolution.cpp` file provides the corrected code.

This example highlights the importance of careful index checking when working with vectors and other dynamic data structures.