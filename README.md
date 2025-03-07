# Selection Sort Algorithm

## Introduction

Selection Sort is a simple comparison-based sorting algorithm that divides the input list into two parts: the sorted and the unsorted section. It repeatedly selects the smallest element from the unsorted section and swaps it with the first unsorted element, gradually building the sorted list.

## How It Works

1. Iterate through the list and find the smallest element.
2. Swap it with the first unsorted element.
3. Move the boundary between sorted and unsorted sections forward.
4. Repeat until the entire list is sorted.

## Time Complexity

- **Best Case:** O(n²) (Still iterates over the array even if it is already sorted)
- **Average Case:** O(n²)
- **Worst Case:** O(n²)

Since Selection Sort always requires O(n²) comparisons, it is not efficient for large datasets.

## Advantages

- Simple and easy to implement.
- Performs well on small lists.
- Requires minimal memory swaps compared to Bubble Sort.

## Disadvantages

- Inefficient for large datasets due to O(n²) complexity.
- Slower compared to more advanced sorting algorithms like Quick Sort or Merge Sort.

## Conclusion

The Selection Sort algorithm effectively sorts a list in ascending order by repeatedly finding the smallest element from the unsorted portion and swapping it with the first unsorted element. Though simple and easy to implement, Selection Sort has a time complexity of O(n²), making it