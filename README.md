# Searching_In_CPP
## Aim
To study and implement searching algorithms in C++.
## Theory
### What are algorithms
An algorithm is a step-by-step set of instructions designed to solve a problem or perform a task, converting input data into a desired output
### Searching
Searching algorithms are essential tools in computer science used to locate specific items within a collection of data. When we search an item in an array, there are two most common algorithms used based on the type of input array.

1. Linear Search : It is used for an unsorted array. It mainly does one by one comparison of the item to be search with array elements. It takes linear or O(n) Time.

   <img width="682" height="400" alt="image" src="https://github.com/user-attachments/assets/924963aa-424f-4320-a5a7-8128ae717637" />


2. Binary Search : It is used for a sorted array. It mainly compares the array's middle element first and if the middle element is same as input, then it returns. Otherwise it searches in either left half or right half based on comparison result (Whether the mid element is smaller or greater). This algorithm is faster than linear search and takes O(Log n) time.

   <img width="1000" height="471" alt="image" src="https://github.com/user-attachments/assets/8ac0b08d-bac3-4949-8eb9-9f621820fa27" />

## Algorithm
### Linear Search
1. A vector/array arr of size n.

2. A target value to search.

3. Return 1 if the element is found, otherwise -1.

4. Set i = 0.

5. Repeat while i < n: If arr[i] == target, then return 1. Otherwise, increment i = i + 1.

### Binary Search
1. A sorted vector/array arr of size n.

2. A target value to search.

3. Return the index of the element if found, otherwise -1.

4. Start.

5. Initialize low = 0, high = n - 1.

6. Repeat while low <= high:
   
a. Compute mid = low + (high - low) / 2.

b. If arr[mid] == target, return mid.

c. If arr[mid] < target, update low = mid + 1.

d. Else, update high = mid - 1.

7. If the loop ends without finding the target, return -1.

8. Stop.

9. If the loop completes without finding the element, return -1. Stop.

## Conclusion
We learnt about algorithms and 2 types of searching algorithms.
