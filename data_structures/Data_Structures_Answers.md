Add your answers to the questions below.

1. What is the runtime complexity of your `depth_first_for_each` method?
R// O(n) because each node is analized only once

2. What is the space complexity of your `depth_first_for_each` function?
R// O(n) where n is the maximum height of the tree as all the ancestors of each node are stored

3. What is the runtime complexity of your `breadth_first_for_each` method?
R// O(n) because each node is analized only once

4. What is the space complexity of your `breadth_first_for_each` method?
R// O(n) where n is the maximum width of the tree as the nodes array stores the nodes at each level

5. What is the runtime complexity of your `heapsort` function?
R// O(n log(n))

6. What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?
R// my function has space complexity of O(n) as it creates a new pivot array. if my function instead altered the input array, it would not require aditional space but only pointers to the existing array, so the space would be constant (O(1))