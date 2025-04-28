Basic way to compile:

nvcc your_file.cu -o output_executable

Example:
Suppose you have a CUDA file named vector_add.cu, you would compile it like this:

nvcc vector_add.cu -o vector_add


To compile a C++ program with OpenMP:

g++ -fopenmp your_file.cpp -o output_executable


-fopenmp tells the compiler to enable OpenMP support.

your_file.cpp is your C++ source file.

-o output_executable is the name of the executable you want.
