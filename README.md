
# High Performance Python - Portfolio of Evidence

## Classroom Activity - High Performance Computing
Date: March 24, 2024
Author: Karla Delgado Avendaño

### Introduction
This repository contains exercises and solutions for improving Python code's performance. It includes benchmarking, profiling, data structure optimizations, and high-level computations.

### Part 1: Benchmarking and Profiling
Implement functions for calculating the Julia Set, utilizing profiling tools like `timeit`, `cProfile`, and `memory_profiler`.

### Part 2: Lists and Tuples
Examine performance for different operations on lists and tuples, especially focusing on insertion and deletion.

### Part 3: Dictionaries and Sets
Analyze changes in "Áreas Geoestadísticas Básicas" (AGEBs) in Mérida Yucatán from 2010 to 2020 using dictionaries and sets.

### Part 4: Matrix and Vector Computations
Focus on array broadcasting, fast array operations with Numpy and Pandas, and optimal performance strategies with `numexpr`.

### Part 5: Compiling to C
Explore various Cython solutions to implement Conway's Game of Life and discuss performance improvements.


## Requirements

To successfully run the notebooks in this repository, you will need to install several Python libraries and ensure your environment is correctly set up. Below is the list of required libraries along with installation commands.

### Core Libraries
These are the primary libraries required for the majority of the code to function properly:

- **Numpy**: For numerical computations.
  ```bash
  pip install numpy
  ```
- **Pandas**: For data manipulation and analysis.
  ```bash
  pip install pandas
  ```
- **Matplotlib**: For plotting and visualization.
  ```bash
  pip install matplotlib
  ```
- **Geopandas**: For geographical data manipulation (ensure dependencies are met).
  ```bash
  pip install geopandas
  ```

### Profiling and Performance Optimization
These libraries are used specifically for profiling and improving code performance:

- **Line_profiler**: For line-by-line profiling.
  ```bash
  pip install line_profiler
  ```
- **Numexpr**: For fast numerical expression evaluation.
  ```bash
  pip install numexpr
  ```
- **Memory_profiler**: For memory usage profiling.
  ```bash
  pip install memory_profiler
  ```
- **cProfile**: Standard library, available in Python.

### Utility Libraries
These are additional libraries used for various utility functions within the notebooks:

- **Time, Timeit, Random**: Standard libraries, available in Python.
- **Array, Collections, Functools**: Standard libraries, available in Python.
