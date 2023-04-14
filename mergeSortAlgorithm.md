# Merge Sort

## What is the Merge Sort?

It is a sorting algorithm used to sort an array of elements. It is a "divide and conquer" algorithm that can handle large data sets efficiently, with a time complexity of **O(n log n)**.

Merge Sort begins by dividing an array into two equal parts. Then, it sorts each part separately. Creates a fully sorted array by combining two sorted subarrays. When combining two substrings, it compares the two sequences and adds the smaller one to the new sequence. This process is completed by merging all substrings.

### Sort this series according to Merge Sort algorithm. -> [16,21,11,8,12,22]

1. step

    Left side: [16,21,11], Right side: [8,12,22]
2. step

    Left side: [16], [21,11], Right side: [8], [12,22]

3. step

    Left side: [16], [21], [11] Right side: [8], [12], [22]

4. step
    
    Left side: [16], [11,21] Right side: [8], [12,22]

5. step

    Left side: [16,11,21] Right side: [8,12,22]

6. step

    Left side: [8,11,12,16,21,22]

### Big O Notation: O(n log n)

The Big O representation of the merge sort algorithm is O(n log n). This means that the running time of the algorithm will increase logarithmically as the number of elements to be sorted (n) increases. That is, the merge sort algorithm is a suitable sorting method for use on large data sets. Merge sort is often preferred for sorting large datasets, as it has more efficient performance compared to other sorting algorithms.