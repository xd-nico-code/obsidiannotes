An array is a data structure which can be defined as finite ordered set of homogeneous elements
- finite (set number of elements)
- ordered (the elements are fixed at a index)
- homogeneous (all elements are of same type)
- contiguous memory (each element is stored as the very next address )
- Random access (no need to iterate through elements to access a element at greater index)

# Arrays in C++

## One-Dimensional Array
- **Linear Collection:** A sequence of elements of the same data type stored in contiguous memory locations.

- **Access:** Elements are accessed using an index, starting from 0.

- **Use Cases:** Representing lists of items like numbers, names, or colors.

    C++
    
    ```
    int numbers[5] = {1, 2, 3, 4, 5}; 
    // declares an array named 'numbers' that can hold 5 integers.
    ```
    

## Multidimensional Array

- **Array of Arrays:** Essentially an array where each element is itself an array. This creates a grid-like structure.
    
- **Dimensions:** Can have two or more dimensions. A 2D array is like a table with rows and columns, a 3D array is like a cube, and so on.
    
- **Access:** Elements are accessed using multiple indices, one for each dimension.
    
- **Use Cases:** Representing tables, matrices, images (where each pixel is an element in a 2D array), and other complex data structures.
    
    C++
    
    ```
    int matrix[3][3] = {  
        {1, 2, 3}, 
        {4, 5, 6}, 
        {7, 8, 9}  
    }; 
    // declares a 2D array named 'matrix' with 3 rows and 3 columns.
    ```
    

## Key Differences

|Feature|One-Dimensional Array|Multidimensional Array|
|---|---|---|
|Structure|Linear|Array of arrays|
|Indexing|Single index|Multiple indices|
|Representation|List|Table, matrix, etc.|
|Memory Allocation|Contiguous|May not be contiguous|
```C++

```