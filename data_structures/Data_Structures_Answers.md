Add your answers to the questions below.

1. What is the runtime complexity of your `depth_first_for_each` method?

2. What is the space complexity of your `depth_first_for_each` function?

3. What is the runtime complexity of your `breadth_first_for_each` method?

    O(n), it has to go through every node to check.

4. What is the space complexity of your `breadth_first_for_each` method?
    O(n), items get added to the queue for every item.

5. What is the runtime complexity of your `heapsort` function?
    O(nlog(n))
    
6. What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?
    O(n), function had to create a sorted list with every item inside. If it worked directly on the array, it doesn't take up any more space and acts in place, so O(c).