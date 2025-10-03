# Experiment-22

Title: Algorithm Analysis Using Big O Notation

Aim: To understand and analyze the efficiency of algorithms using Big O notation, focusing on time and space complexity.

Software Required: Visual Studio (or any C++ compiler)

Theory: Algorithm analysis is a fundamental concept in computer science that evaluates the performance of algorithms in terms of time and space. The goal is to determine how an algorithm scales with input size and to compare different algorithms based on their efficiency. The most widely used method for this analysis is Big O notation, which describes the upper bound of an algorithm's growth rate.

Big O notation provides a mathematical framework to express the worst-case, average-case, and best-case performance of an algorithm. It abstracts away hardware and implementation details, focusing solely on how the algorithm behaves as the input size increases.

Time Complexity:
Time complexity measures the amount of time an algorithm takes to complete as a function of the input size nn. Common time complexities include:
O(1) – Constant time: Execution time does not depend on input size.
O(log n) – Logarithmic time: Efficient for divide-and-conquer algorithms like Binary Search.
O(n) – Linear time: Time grows proportionally with input size.
O(n log n) – Linearithmic time: Common in efficient sorting algorithms like Merge Sort and Quick Sort.
O(n²) – Quadratic time: Seen in nested loops, e.g., Bubble Sort and Selection Sort.
O(2ⁿ) – Exponential time: Very inefficient, often found in brute-force recursive algorithms.

Space Complexity:
Space complexity refers to the amount of memory an algorithm uses relative to the input size. It includes both the input storage and auxiliary space required during execution.
O(1) – Constant space: No extra memory used.
O(n) – Linear space: Memory usage grows with input size.
O(n²) – Quadratic space: Used in algorithms that store pairwise combinations or matrices.

Why Big O Matters:
Predictability: Helps estimate performance before implementation.
Scalability: Determines how well an algorithm handles large inputs.
Optimization: Guides developers in choosing the most efficient algorithm for a task.

Conclusion: In this report, we explored the concept of algorithm analysis using Big O notation. Big O provides a standardized way to evaluate and compare the efficiency of algorithms in terms of time and space. By understanding time and space complexity, programmers can make informed decisions about which algorithms to use based on the size and nature of the data. This knowledge is essential for writing optimized, scalable, and high-performance code in real-world applications.
