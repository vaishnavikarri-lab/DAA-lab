Practical-1
Summary

This lab practical includes the implementation of five sorting algorithms: Selection Sort, Merge Sort, Bubble Sort,
Insertion Sort, and Quick Sort. Each program takes input from the user, sorts the data in ascending order,
and shows the execution time. It also explains the time and space complexity of each algorithm. Selection Sort
takes the same amount of time in every case, making it less suitable for large amounts of data. Bubble Sort 
and Insertion Sort work faster when the data is already or almost sorted, but they take more time for random data. 
Merge Sort gives good performance in all cases and is suitable for handling large datasets, although it uses extra memory.
Quick Sort is also very fast for most cases and is one of the most commonly used sorting algorithms, but in some situations 
it can take more time. This practical helps in understanding how different sorting methods work and how their performance 
changes with different types of input.

Conclusion

This practical helped in understanding the working of different sorting algorithms and comparing their performance. 
By checking the execution time and studying the time and space complexity of each algorithm, it became easier to 
know where each sorting method is useful. Simple algorithms like Selection Sort, Bubble Sort, and Insertion Sort 
are easy to understand and work well for small datasets. Merge Sort and Quick Sort are better choices for larger datasets
because they are faster in most cases. Overall, this practical improved the understanding of sorting techniques 
and showed why choosing the right algorithm is important for writing efficient programs.


Practical-2
Summary

In this practical, I implemented two searching algorithms in Python: **Linear Search** and **Binary Search**. 
Both programs take input from the user and search for a given element in an array.
In **Linear Search**, each element is checked one by one until the required element is found or the complete array is checked. 
It works on both sorted and unsorted arrays.
In **Binary Search**, the array must be sorted. The algorithm repeatedly divides the search range into two halves and 
checks the middle element. This makes Binary Search faster than Linear Search for large sorted arrays.
The programs also display the number of comparisons, actual execution time, and time complexity for the best, average, and worst cases.

Conclusion

In this practical, I learned how to implement **Linear Search** and **Binary Search** using Python. Linear Search checks 
each element one by one and can work with both sorted and unsorted arrays. Binary Search is faster because it divides the search 
range into two parts, but it requires the array to be sorted.

I also learned about the **best, average, and worst-case time complexity** of both algorithms. Linear Search has a time complexity
of **O(1)** in the best case and **O(n)** in the average and worst cases. Binary Search has **O(1)** in the best case and 
**O(log n)** in the average and worst cases. The practical also helped me understand how to count comparisons and measure
the actual execution time of an algorithm.


Practical-3
Summary

In this practical, we implemented the Max Heap Sort algorithm using Python to sort a list of elements in ascending order. The program takes the number of elements and the elements from the user as input. The given elements are first arranged into a Max Heap, where the largest element is always placed at the root. After creating the Max Heap, the largest element is moved to the end of the array, and the remaining elements are heapified again. This process continues until all the elements are placed in their correct positions. The program also displays the best-case, average-case, and worst-case time complexity of the algorithm. Through this practical, we learned the basic working of a Max Heap, how heapify is used during sorting, and how Heap Sort can be used to arrange elements efficiently.

Conclusion

From this practical, we learned how to implement Max Heap Sort and understood how it works step by step. We learned that a Max Heap always keeps the largest element at the root, which makes it easier to place the largest element at the end of the array during each step of sorting. We also understood the role of the heapify function in maintaining the Max Heap after each element is removed. Heap Sort has a time complexity of O(n log n) in the best, average, and worst cases. This means that its performance remains consistent even when the input elements are already sorted or arranged in reverse order. Overall, this practical helped us understand the working of Max Heap Sort, the use of heapify, and the importance of understanding the time complexity of an algorithm.


Practical-4
Summary

In this practical, we implemented and analyzed the factorial program using both iterative and recursive methods in Python. The program accepts a number from the user and calculates its factorial using both approaches. We also measured the actual implementation time of each method using Python's time measurement function. Along with the execution time, we studied the best-case, average-case, and worst-case time complexity of both methods. The analysis showed that both iterative and recursive approaches have a time complexity of O(n). However, their space requirements are different. The iterative method uses O(1) auxiliary space, whereas the recursive method uses O(n) space because each recursive function call is stored in the call stack. This practical helped us understand how the same problem can be solved using different approaches and how algorithm efficiency can be evaluated.

Conclusion

From this practical, we learned that choosing an appropriate approach is important when implementing an algorithm. Both iterative and recursive methods successfully calculate the factorial and produce the same result, but they differ in memory usage and implementation style. The iterative method is more memory-efficient because it does not create multiple function calls, while the recursive method provides a simple and easy-to-understand representation of the factorial formula. We also learned that actual implementation time can vary depending on the system and should not be confused with theoretical time complexity. Overall, this practical improved our understanding of algorithm implementation, recursion, iteration, execution-time measurement, and complexity analysis, which are important concepts for designing efficient programs.


Practical-7
Summary

In this practical, we implemented the Making Change Problem using Dynamic Programming in Python. The program takes the coin denominations and the required amount as input from the user and determines the minimum number of coins required to make the given amount. Dynamic Programming is used to store the results of smaller subproblems and reuse them instead of solving the same problems repeatedly. We also measured the actual implementation time of the program and analyzed its efficiency. The time complexity of the approach is O(A × N), where A is the required amount and N is the number of available coin denominations. The space complexity is O(A) because a DP table of size proportional to the amount is maintained. This practical helped us understand how Dynamic Programming can improve problem-solving efficiency by avoiding unnecessary repeated calculations.

Conclusion

From this practical, we learned how the Making Change Problem can be efficiently solved using Dynamic Programming. Instead of checking every possible combination of coins, the algorithm builds the solution step by step using previously calculated results. This makes the approach systematic and efficient, especially when the amount becomes larger. We also learned how to measure the actual execution time and compare it with the theoretical time complexity of an algorithm. The best, average, and worst-case time complexity for this implementation is O(A × N), while its space complexity is O(A). Overall, this practical gave us a clear understanding of Dynamic Programming, optimal subproblems, time and space complexity, and practical performance analysis, which are important for designing efficient algorithms.


Practical-6
Summary

In this practical, Chain Matrix Multiplication is implemented using **Dynamic Programming**. The purpose is to find the best order in which a group of matrices should be multiplied so that the number of calculations is as small as possible. The program takes the number and dimensions of matrices from the user and checks different possible multiplication orders to find the one with the minimum cost.
The program uses two tables. The **Cost Table** stores the minimum number of calculations needed for multiplying different groups of matrices. The **Split Table** stores the position where the matrices should be divided to get the best result. The program also displays the best multiplication order and the actual execution time. The time complexity of the program is **O(n³)** for the best, average, and worst cases, and the space complexity is **O(n²)**.

Conclusion

The Chain Matrix Multiplication problem was successfully solved using Dynamic Programming. The program finds the best multiplication order and reduces the number of calculations needed. The Cost Table helps us find the minimum cost, while the Split Table helps us find where to divide the matrices. This practical helped in understanding how Dynamic Programming can be used to solve a problem by solving smaller parts and storing their results for later use. It also helped us understand the execution time and time and space complexity of the algorithm.


Practical-8
Summary

In this practical, we implemented Graph Searching using Depth First Search (DFS) and Breadth First Search (BFS) in Python. The graph was represented using two different methods: Adjacency List and Adjacency Matrix. For DFS, we used recursion to visit a vertex and then explore its connected vertices deeply before moving to another path. For BFS, we used a queue to visit the vertices level by level. Both DFS and BFS were performed using the same graph, and the traversal order was observed. This practical helped us understand how different graph representations can be used for searching and traversal.

Conclusion

From this practical, we learned how to create and represent a graph using an Adjacency List and Adjacency Matrix. We also learned the working of DFS and BFS traversal techniques and their implementation in Python. DFS explores the graph deeply, while BFS explores the graph level by level. The practical helped us understand the difference between these two searching methods and how they can be applied to solve different graph-related problems. Thus, DFS and BFS are important graph traversal techniques used in many computer science applications.


Practical-9
Summary

In this practical, we implemented Prim’s Algorithm in Python to find the Minimum Spanning Tree (MST) of a weighted graph. The graph was represented using an adjacency matrix, where each value represents the weight of an edge between two vertices. Prim’s Algorithm starts with one vertex and repeatedly selects the minimum-weight edge that connects a selected vertex to an unselected vertex. This process continues until all vertices are included in the Minimum Spanning Tree.

Conclusion

From this practical, we learned how Prim’s Algorithm is used to find a Minimum Spanning Tree of a weighted graph. We understood how to select the minimum-weight edges while avoiding unnecessary connections and how to calculate the total cost of the MST. The implementation also helped us understand the use of adjacency matrices in graph problems. Prim’s Algorithm is useful for connecting all vertices with minimum total cost, such as in network and infrastructure design.
