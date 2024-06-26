![LongLeaf Logo](https://github.com/ChrisWhisker/longleaf-lib/assets/6521800/ce065792-c6eb-4644-a54c-4e7e25c94f47)

# LongLeaf Library: C++ Data Structures, Algorithms, and Design Patterns

This repository serves as a demonstration of implementations of common data structures, algorithms, and design patterns in C++. The primary focus is on memory efficiency and reducing dependencies on the C++ Standard Template Library (STL). By providing efficient solutions without relying heavily on the STL, this repository aims to offer insights into building robust and resource-conscious software systems.

## Purpose

The purpose of this repository is twofold:

1. **Demonstrate Efficient Implementations:** The implementations showcased here prioritize memory efficiency and minimize reliance on the C++ STL. This approach is beneficial for environments with restricted standard library support or where manual memory management is preferred.

2. **Educational Resource:** Developers can use this repository as a learning resource to understand the inner workings of common data structures, algorithms, and design patterns in C++. By examining the code and studying the provided implementations, developers can enhance their understanding of fundamental concepts in computer science and software engineering.

## Classes

### Data Structures
  - [Array](/LongLeaf/data_structures/Array.h)
  - [Linked list](/LongLeaf/data_structures/LinkedList.h)
  - [Stack](/LongLeaf/data_structures/Stack.hh)
### Algorithms
  - Searching
    - [Binary search](/LongLeaf/search/BinarySearch.h)
  - Sorting
    - [Merge sort](/LongLeaf/sort/MergeSort.h)
    - [Quick sort](/LongLeaf/sort/QuickSort.h)
### Utilities (static functions for C-style array and string management)
  - [Array Utils](/LongLeaf/utils/ArrayUtils.h)
  - [String Utils](/LongLeaf/utils/StringUtils.h)
### Design Patterns
  - [Strategy pattern](/LongLeaf/design_patterns/Strategy.h)

## Key Features

- **Memory-Efficient Implementations:** The implementations emphasize efficient memory usage, making them suitable for resource-constrained environments or situations where manual memory management is desired.

- **Reduced Dependencies:** The codebase minimizes dependencies on the C++ STL, providing alternative solutions for scenarios where standard library support may be limited or unavailable.

- **Focus on Common Data Structures, Algorithms, and Design Patterns:** In addition to data structures and algorithms, this repository includes examples of common design pattern implementations, enriching the learning experience for developers.

## Contributions

Contributions to this repository are encouraged. If you have improvements, optimizations, or additional implementations to contribute, feel free to open a pull request. Please ensure that your contributions align with the repository's focus on memory efficiency and avoiding dependencies.
