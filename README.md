# Selection-sort
Selection sort is a simple sorting algorithm that sorts an array by repeatedly finding the minimum element from the unsorted part of the array and putting it at the beginning of the sorted part of the array.
# Algoritm
Here is a detailed explanation of how the selection sort algorithm works:

1. Iterate through the array to be sorted and find the smallest element.
2. Swap the smallest element with the first element of the array.
3. Repeat step 1 and step 2 with the remaining unsorted part of the array, moving from the second element to the end of the array.
4. Repeat steps 1-3 until the entire array is sorted.
# Explaination Example
Let's take an example to illustrate how selection sort works. Consider the following list of integers:

[5, 2, 8, 3, 6]

We start by finding the smallest element in the entire array, which is 2. We then swap 2 with the first element of the array:

[2, 5, 8, 3, 6]

Next, we find the smallest element in the remaining unsorted part of the array (excluding the first element), which is 3. We swap 3 with the second element of the array:

[2, 3, 8, 5, 6]

We continue this process, finding the smallest element in the remaining unsorted part of the array and swapping it with the appropriate element in the sorted part of the array. After the third iteration, the array looks like this:

[2, 3, 5, 8, 6]

We repeat the process until the entire array is sorted. After the fourth iteration, the final sorted array is:

[2, 3, 5, 6, 8]

Selection sort has a time complexity of O(n^2), which means that it is not efficient for large data sets. However, it is simple to understand and implement, and it can be a good choice for small data sets or as a component of more complex sorting algorithms.
# Application
1. Selection sort can be useful in situations where the data set to be sorted is small or the memory usage is limited. It is simple to implement and requires only a constant amount of additional memory.

2. One common application of selection sort is in sorting small arrays or lists of data. Selection sort has a time complexity of O(n^2), which means that it is not efficient for large data sets. However, for small data sets, the overhead of more efficient algorithms may outweigh the benefits.

3. Selection sort can also be used as a component of other sorting algorithms, such as the shell sort and the heap sort. These algorithms build on the basic principles of selection sort to create more efficient and effective sorting methods.

4. Selection sort can be used as a teaching tool to introduce students to the concept of sorting algorithms. Its simplicity makes it easy to understand and implement, and it can be a good starting point for learning more advanced sorting algorithms.
# Screenshot
![p4](https://user-images.githubusercontent.com/126184012/234289334-beb34256-9f0d-4ce1-b2b2-4224cb2fadc6.png)
