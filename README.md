# Sorting Visualizer

This is a sorting algorithm visualizer implemented in C++ using the SDL2 library. The visualizer demonstrates the working of different sorting algorithms by displaying the sorting process in real-time.

## Introduction

Visualization of sorting algorithms is an effective way to understand their working and performance characteristics. This sorting visualizer provides a graphical representation of various sorting algorithms, allowing users to observe the sorting process step by step.

The sorting algorithms covered in this visualizer include:

Selection Sort

Insertion Sort

Bubble Sort

Merge Sort

Quick Sort

Heap Sort

The list size is fixed at 130 elements, and the algorithms sort the elements in ascending order. The visualized sorting time may not directly reflect the actual time complexity of the algorithms, as certain algorithms have been intentionally delayed for better visualization.

## Usage

Once you have successfully compiled the project, you can run the sorting visualizer by executing the generated binary or running it from an IDE.

The visualizer displays a window showing a bar chart representing the elements to be sorted. Each sorting algorithm can be invoked using specific key inputs. The sorting process will be displayed in the window, allowing you to observe the algorithm's progress step by step.

To interact with the visualizer, use the following controls:

Press 0 to generate a new randomized list.
Press 1 to start the Selection Sort algorithm.
Press 2 to start the Insertion Sort algorithm.
Press 3 to start the Bubble Sort algorithm.
Press 4 to start the Merge Sort algorithm.
Press 5 to start the Quick Sort algorithm.
Press 6 to start the Heap Sort algorithm.
Press q to exit the visualizer.


## Available Sorting Algorithms

### 1. Selection Sort
Selection Sort is an in-place comparison sorting algorithm. It repeatedly finds the minimum element from the unsorted part of the array and swaps it with the element at the beginning of the unsorted part.

### 2. Insertion Sort
Insertion Sort is a simple sorting algorithm that builds the final sorted array one element at a time. It iterates through the array, comparing each element with the previous elements and inserts it into its correct position in the sorted part of the array.

### 3. Bubble Sort
Bubble Sort is a simple sorting algorithm that repeatedly swaps adjacent elements if they are in the wrong order. It continues to pass through the array until the entire array is sorted.

### 4. Merge Sort
Merge Sort is a divide-and-conquer algorithm that divides the input array into two halves, recursively sorts them, and then merges the sorted halves to obtain a final sorted array. It is an efficient sorting algorithm with a time complexity of O(n log n).

### 5. Quick Sort
Quick Sort is another divide-and-conquer algorithm that selects a pivot element and partitions the array around the pivot. It recursively sorts the sub-arrays before and after the pivot. Quick Sort has an average time complexity of O(n log n).

### 6. Heap Sort
Heap Sort is a comparison-based sorting algorithm that builds a binary heap from the input array and repeatedly extracts the maximum element from the heap and places it at the end of the sorted array. It has a time complexity of O(n log n) and is often used for large datasets.


## Controls

The visualizer provides the following controls:

0: Generate a new randomized list.
1: Start Selection Sort.
2: Start Insertion Sort.
3: Start Bubble Sort.
4: Start Merge Sort.
5: Start Quick Sort.
6: Start Heap Sort.
q: Exit the visualizer.

Please note that giving repetitive commands may cause latency and unexpected behavior. Wait for the current command's execution to complete before giving a new command.


## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request on GitHub.
