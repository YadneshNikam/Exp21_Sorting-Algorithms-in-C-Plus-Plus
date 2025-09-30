# Exp21_Sorting-Algorithms-in-C-Plus-Plus

### Aim  
To study and implement sorting algorithms in C++.

### Software Required  
Visual Studio.

### Theory  
Sorting algorithms rearrange elements in an array or list into a specified order, such as ascending or descending. Different algorithms suit different types of input, such as arrays with duplicates, varying sizes, or special value ranges. Some sorting algorithms maintain the original order of equal elements (stable sort), while others do not. Most programming languages offer built-in sorting functions for general use.

Three common sorting algorithms are:

- **Selection Sort**: This comparison-based algorithm repeatedly selects the smallest (or largest) element from the unsorted portion and swaps it with the first unsorted element. This process continues until the entire array is sorted. For example, the smallest element is found and placed at the start, then the second smallest is found and placed next, and so on.

- **Bubble Sort**: It repeatedly compares adjacent elements and swaps them if they are in the wrong order. After each pass, the largest unsorted element "bubbles" to its correct position at the end. This process repeats until the whole array is sorted. Although simple, it is inefficient for large datasets.

- **QuickSort**: A divide-and-conquer algorithm that picks a pivot element and partitions the array around it, placing smaller elements to the left and larger elements to the right. The process recurses on the partitions until the array is fully sorted. Choosing a pivot effectively is key to performance.

### Full Algorithm: Selection Sort

1. Start with the first element (index $$i = 0$$) and assume it is the minimum element.

2. Traverse the rest of the array (from $$j = i+1$$ to $$n-1$$) to find the actual minimum element in the unsorted portion.

3. If a smaller element than the assumed minimum is found, update the minimum index.

4. After completing the inner traversal, swap the element at index $$i$$ with the element at the minimum index.

5. Increment $$i$$ and repeat steps 2-4 until the array is fully sorted.

6. The array is sorted when $$i$$ reaches $$n-2$$ since the last element will be in the correct position.

### Implementation  
The sorting concepts are demonstrated with C++ programs implementing:  
- Selection Sort  
- Bubble Sort  
- QuickSort  

### Algorithm Summaries  
- **Selection Sort**: Iterate over array, repeatedly select the minimum from unsorted part and swap it to the front.  
- **Bubble Sort**: Repeatedly swap adjacent out-of-order pairs across multiple passes.  
- **QuickSort**: Partition array around pivot, recursively sort left and right partitions.

### Conclusion  
These samples show various strategies to sort arrays efficiently in C++, adapting to varied input types and performance requirements.

[8](https://interviewkickstart.com/blogs/learn/selection-sort)
[9](https://www.ccbp.in/blog/articles/c-program-for-selection-sort)
[10](https://unstop.com/blog/selection-sort)
