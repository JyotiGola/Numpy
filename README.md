# Numpy
# NumPy Problems & Solutions

## Overview
This repository contains solutions to various NumPy problems, covering essential NumPy functions and operations. The solutions demonstrate efficient ways to manipulate arrays, perform mathematical computations, and optimize data handling using NumPy.

## Problems Covered
Below are some of the key problems solved in this repository:

### 1. Subtracting the Mean of Each Row
- Compute the mean of each row and subtract it from all elements in that row.
- Solution: `np.mean(A, axis=1, keepdims=True)` and broadcasting.

### 2. Swapping Rows and Columns
- Swap two rows or columns in a NumPy array using slicing.
- Solution: `A[[row1, row2]] = A[[row2, row1]]` (for rows), `A[:, [col1, col2]] = A[:, [col2, col1]]` (for columns).

### 3. Finding the N-th Largest Element
- Use `np.partition()` to efficiently find the N-th largest element.
- Solution: `np.partition(A, -N)[-N]`.

### 4. Fetching Every Alternate Column
- Use slicing to extract alternate columns from a 2D array.
- Solution: `A[:, ::2]`.

### 5. Sorting an Array in Descending Order
- Use `np.sort()` with slicing.
- Solution: `np.sort(A)[::-1]`.

### 6. Using `np.tile()` for Repeating Arrays
- Repeat an entire array multiple times along different axes.
- Solution: `np.tile(A, (m, n))`.

### 7. Using `np.repeat()` to Repeat Elements
- Repeat each element in an array multiple times.
- Solution: `np.repeat(A, repeats, axis)`.


