# Time Complexity & Space Complexity Cheat Sheet

## Time Complexity Cheat Sheet of all Searching and Sorting Algorithms
| **Algorithm**    | **Best Time Complexity** | **Average Time Complexity** | **Worst Time Complexity** | **Worst Case Space Complexity** |
| :--------------: | :------------------:| :---------------------: | :-------------------: | :--------------: |
| **Linear Search** | O(1) | O(n) | O(n) | O(1) |
| **Binary Search** | O(1) | O(log n) | O(log n) | O(1)|
| **Selection Sort** | O(n^2) | O(n^2) | O(n^2) | O(1)|
| **Bubble Sort** | O(n) | O(n^2) | O(n^2) | O(1)|
| **Insertion Sort** | O(n) | O(n^2) | O(n^2) | O(1)|
| **Heap Sort** | O(n log(n)) | O(n log(n)) | O(n log(n)) | O(n)|
| **Merge Sort** | O(n log(n)) | O(n log(n)) | O(n log(n)) | O(n)|
| **Quick Sort** | O(n log(n)) | O(n log(n)) | O(n^2) | O(log n)|
| **Bucket Sort** | O(n+k) | O(n+k) | O(n^2) | O(n)|
| **Count Sort** | O(n+k) | O(n+k) | O(n+k) | O(k)|
| **Radix Sort** | O(nk) | O(nk) | O(nk) | O(n+k)|


### Time Complexity:
  **Time complexity** gives the 'idea' of the amount of the time taken by an algorithm as a function of the input size.
  
There are 3 types of notations:
1.	Worst case = (Big O) notation
2.	Best case = (Big Omega) notation
3.	Average case = (Big Theta) notation

Example of Big O Notation **Higher** to **Lower Time Complexities**:
* O(n!)  <Factorial Time>
* O(2^n)
* O(n^3)
* O(n^2)
* O(n log (n))
* O(n)  <Linear Time>
* O(log n)  <Binary Search Time>
* O(1)  <Constant Time>


### Space Complexity:
**Space Complexity** gives the 'idea' of the amount of space required by a program with respect to the input.

#### <ins>O(1) Space Complexity Examples-</ins>
1. int a;
2. int a, b, c, d;
3. int arr[1000];


#### <ins>O(n) Space Complexity Examples-</ins>
1. int arr[n];  // Bad practice
2. vector<int> arr(n);
