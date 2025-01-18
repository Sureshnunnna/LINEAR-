## Bubble Sort Implementation in C

This project demonstrates the implementation of the Bubble Sort algorithm in the C programming language. Bubble Sort is a simple comparison-based sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Output](#output)
- [Time Complexity](#time-complexity)
- [License](#license)

---

## Overview
This program sorts an array of integers in ascending order using the Bubble Sort algorithm. The implementation demonstrates the use of functions to:
- Swap two elements in the array.
- Perform the Bubble Sort.
- Print the array.

## Features
- Simple and clear implementation of Bubble Sort.
- Easy to understand for beginners learning sorting algorithms in C.
- Prints the sorted array to the console.

## How It Works
1. Compares adjacent elements in the array.
2. Swaps the elements if they are in the wrong order.
3. Repeats this process for every element until the array is sorted.

## Usage
### Prerequisites
- A C compiler (e.g., GCC).

### Steps to Run
1. Copy the code into a file named `bubble_sort.c`.
2. Open a terminal and navigate to the directory containing the file.
3. Compile the program using the following command:
   ```bash
   gcc bubble_sort.c -o bubble_sort
   ```
4. Run the program:
   ```bash
   ./bubble_sort
   ```
5. The sorted array will be printed to the console.

## Code Explanation
### `swap` Function
Swaps two elements in the array using pointers.

### `bubbleSort` Function
Performs the Bubble Sort by iterating through the array and swapping adjacent elements when needed.

### `printArray` Function
Prints the array elements to the console.

### `main` Function
1. Initializes an array with sample data.
2. Calls `bubbleSort` to sort the array.
3. Uses `printArray` to display the sorted array.

## Output
Given the input array `{5, 1, 4, 2, 8}`, the program outputs:
```
Sorted array:
1 2 4 5 8
```

## Time Complexity
- **Best Case:** O(n) (when the array is already sorted with optimization).
- **Average Case:** O(n²).
- **Worst Case:** O(n²).


