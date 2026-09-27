# Advanced Puzzles

## 50 Practice Questions with Answers and Explanations

1. You have a 5-liter jug and a 3-liter jug and need exactly 1 liter. How do you do it?

##### Answer :
-  **Use the 5-liter jug to leave 1 liter behind**

##### Explanation:

> Fill the 5-liter jug, pour it into the 3-liter jug until the 3-liter jug is full. This leaves 2 liters in the 5-liter jug. Empty the 3-liter jug, transfer the 2 liters, refill the 5-liter jug, and pour into the 3-liter jug until it is full. Exactly 1 liter remains in the 5-liter jug.

2. A deck of 52 cards is shuffled. What is the probability the first card is a king or the second card is a queen?

##### Answer :
-  **4/52 + 4/52 - (4/52 × 4/51) ≈ 15.7%**

##### Explanation:

> Use inclusion-exclusion because the two events may overlap.

3. You are in a 2D maze and you can only move east or north. How many unique paths are there from one corner to the opposite?

##### Answer :
-  **C(m+n, m)**

##### Explanation:

> Each path is a sequence of east and north moves, and the total number of paths is a binomial coefficient.

4. What is the maximum number of regions formed by n lines in general position?

##### Answer :
-  **n(n+1)/2 + 1**

##### Explanation:

> Each new line intersects all previous lines at distinct points and splits the plane into one more region than before.

5. An array contains duplicate numbers. How do you find the repeated element in O(n) time without extra space?

##### Answer :
-  **Use Floyd cycle detection or a bitwise approach**

##### Explanation:

> In a list where numbers repeat, cycle detection or a mathematical property can find the duplicate in linear time without additional storage.

6. In a binary tree, how do you determine if it is balanced?

##### Answer :
-  **Check the height of each subtree recursively and ensure the height difference is at most 1**

##### Explanation:

> A balanced tree keeps the left and right subtree heights close together.

7. Given a graph with positive weights, how do you find the shortest path from a source to all nodes?

##### Answer :
-  **Use Dijkstra's algorithm**

##### Explanation:

> It works by always choosing the smallest known distance and relaxing neighbors until all shortest paths are known.

8. How do you detect a cycle in an undirected graph?

##### Answer :
-  **Run DFS with a parent pointer**

##### Explanation:

> If you revisit a node that is not the parent, the graph contains a cycle.

9. How many times does the digit 7 appear from 1 to 1000?

##### Answer :
-  **300**

##### Explanation:

> The digit appears 20 times in each hundred block, plus 100 times in the 700-799 block.

10. A function is called recursively with n decreasing by 1. What is its time complexity?

##### Answer :
-  **O(n)**

##### Explanation:

> Each call reduces the problem by one, creating a chain of length n.

11. A process runs 10 tasks concurrently. What is the deadlock condition, and how do you prevent it?

##### Answer :
-  **Deadlock occurs when processes wait on a circular chain of resources**

##### Explanation:

> A deadlock exists when no process can proceed because each is waiting on another. Prevent it with lock ordering, timeouts, or disciplined resource allocation.

12. A system has 3 servers and one request can be processed by any server. How do you maximize throughput while maintaining fault tolerance?

##### Answer :
-  **Add a load balancer and health checks with replicated servers**

##### Explanation:

> This distributes requests evenly and keeps the system available even if one server fails.

13. In a distributed system, what is the difference between consistency, availability, and partition tolerance?

##### Answer :
-  **Consistency means the same data view; availability means the system responds; partition tolerance means it keeps working during a network split**

##### Explanation:

> CAP states that a distributed system can guarantee at most two of the three properties at the same time.

14. There are 100 prisoners and 100 boxes, each containing a prisoner's number. How can they maximize the chance to find their own number?

##### Answer :
-  **Each prisoner follows the box-number chain**

##### Explanation:

> Each prisoner opens the box matching their number and continues following the chain until they find their own number or fail after 50 attempts. This strategy succeeds with high probability.

15. If 8 people sit around a round table, how many unique circular arrangements are there?

##### Answer :
-  **7! = 5040**

##### Explanation:

> Rotations are considered the same in a circle, so divide the total number of permutations by 8.

16. You have a function that returns the maximum element in an array. The array is unsorted. What is the best possible complexity?

##### Answer :
-  **O(n)**

##### Explanation:

> In the worst case, every item must be inspected to know the maximum.

17. A number is chosen randomly from 1 to 100. What is the probability it is divisible by 3 or 5?

##### Answer :
-  **47/100**

##### Explanation:

> There are 33 multiples of 3, 20 multiples of 5, and 6 overlap values, giving 47 unique numbers.

18. A list is sorted in ascending order. What is the complexity of binary search?

##### Answer :
-  **O(log n)**

##### Explanation:

> Each step halves the remaining search space.

19. A staircase can be climbed in 1 or 2 steps. How many ways can you climb 20 steps?

##### Answer :
-  **10946**

##### Explanation:

> This follows the Fibonacci recurrence: F(n) = F(n-1) + F(n-2).

20. How many ways can you arrange 5 books on a shelf?

##### Answer :
-  **5! = 120**

##### Explanation:

> A shelf arrangement is simply a permutation of five distinct books.

21. If a coin is flipped 10 times, what is the probability of getting exactly 5 heads?

##### Answer :
-  **C(10,5)/2^10 = 252/1024 ≈ 24.6%**

##### Explanation:

> We choose 5 positions for heads out of 10 flips and divide by all possible outcomes.

22. A string is a palindrome if reversed equals itself. How do you check this efficiently?

##### Answer :
-  **Compare the first and last characters, moving inward**

##### Explanation:

> This approach runs in O(n) time and O(1) extra space.

23. In a priority queue, what is the time complexity of extracting the maximum element?

##### Answer :
-  **O(log n)**

##### Explanation:

> A priority queue is typically implemented with a heap, and extraction takes logarithmic time.

24. There are 50 red balls and 50 blue balls. You pick 2 without replacement. What is the probability both are red?

##### Answer :
-  **C(50,2)/C(100,2) ≈ 49.5%**

##### Explanation:

> You choose 2 red balls out of 50 and divide by all possible 2-ball combinations.

25. How do you find the median of an unsorted array in linear time?

##### Answer :
-  **Use a linear-time selection algorithm such as median-of-medians**

##### Explanation:

> This avoids sorting the entire array and still finds the middle element.

26. Given two linked lists, how do you detect if they intersect?

##### Answer :
-  **Use two pointers with length adjustment**

##### Explanation:

> Traverse both lists with two pointers and adjust for length difference. When the pointers meet, the lists intersect.

27. A hash map has collisions. How do you resolve them?

##### Answer :
-  **Use separate chaining or open addressing**

##### Explanation:

> Both methods handle multiple keys that hash to the same bucket without losing lookup behavior.

28. A sorted array has duplicates. How do you find the first index of a target in O(log n)?

##### Answer :
-  **Use binary search on the leftmost matching index**

##### Explanation:

> Keep searching left while the value matches the target to ensure the first occurrence is returned.

29. A binary search tree is not balanced. What happens to insertion and lookup times?

##### Answer :
-  **They degrade to O(n) in the worst case**

##### Explanation:

> An unbalanced BST can behave like a linked list, making operations linear.

30. Suppose you have a stream of data and need to return the top K frequent items. How do you do it efficiently?

##### Answer :
-  **Use a hash map for counts and a min-heap of size K**

##### Explanation:

> This keeps the most frequent items without re-scanning the entire stream.

31. In a system with 3 processes competing for 2 resources, how can a deadlock arise?

##### Answer :
-  **Process A holds X and waits for Y while process B holds Y and waits for X**

##### Explanation:

> This creates a circular wait, which is one of the necessary conditions for deadlock.

32. What is the difference between a stack and a queue?

##### Answer :
-  **A stack is LIFO and a queue is FIFO**

##### Explanation:

> The ordering of insertion and removal defines their behavior.

33. Explain the CAP theorem in one sentence.

##### Answer :
-  **A distributed system can guarantee at most two of consistency, availability, and partition tolerance**

##### Explanation:

> Partition tolerance is often required in real systems, so teams usually choose between consistency and availability.

34. If a function runs in O(log n) time, how does doubling the input affect runtime?

##### Answer :
-  **It adds only a constant amount of time**

##### Explanation:

> Logarithmic growth is very slow, so doubling the input increases the runtime by a fixed increment.

35. How would you design a rate limiter for an API?

##### Answer :
-  **Use a token bucket or leaky bucket algorithm**

##### Explanation:

> This limits requests over a time window and prevents overload.

36. How do you detect whether a binary tree is a valid BST?

##### Answer :
-  **Perform an inorder traversal and check that values are sorted**

##### Explanation:

> In-order traversal of a BST should produce sorted values, or you can maintain min/max bounds.

37. A string contains parentheses. How do you check if the sequence is balanced?

##### Answer :
-  **Use a stack**

##### Explanation:

> Push opening brackets and pop them when closing brackets appear. If the stack is empty at the end, the sequence is balanced.

38. What is the time complexity of mergesort?

##### Answer :
-  **O(n log n)**

##### Explanation:

> It divides the array into halves and then merges the sorted halves recursively.

39. If 20% of the population has some trait and a test is 90% accurate, what is the probability a positive test result is actually correct?

##### Answer :
-  **About 33.3%**

##### Explanation:

> A large number of positives come from a small base rate, so a test can be accurate while still producing many false positives.

40. A lock has 3 wheels with digits 0-9. How many possible combinations are there?

##### Answer :
-  **1000**

##### Explanation:

> Each wheel has 10 choices, so 10 × 10 × 10 = 1000.

41. A carousel rotates by 90 degrees every second. How do you compute its position after 10 seconds?

##### Answer :
-  **900°, equivalent to 180° after modulo 360°**

##### Explanation:

> Rotations repeat every 360°, so reduce the angle modulo 360°.

42. You have a graph with 100 vertices and 200 edges. Is it guaranteed to have a cycle?

##### Answer :
-  **Yes, likely**

##### Explanation:

> A connected graph with 100 vertices and 200 edges has enough edges to create cycles.

43. If a system has a 1-second timeout and 5 concurrent requests, how would you prevent a thundering herd?

##### Answer :
-  **Use jittered retries and a shared cache or rate limiter**

##### Explanation:

> Staggering retries prevents a synchronized retry storm after a timeout.

44. How do you find the longest increasing subsequence in an array?

##### Answer :
-  **Use patience sorting or dynamic programming**

##### Explanation:

> The LIS is the longest sequence of increasing values in order, not necessarily contiguous.

45. You receive an array where every number appears twice except one. How do you find the unique number?

##### Answer :
-  **Use XOR on all numbers**

##### Explanation:

> XOR cancels identical values and leaves only the unique one.

46. A process can access the same memory from multiple threads. How do you prevent race conditions?

##### Answer :
-  **Use mutexes, semaphores, or atomic operations**

##### Explanation:

> Synchronization ensures that critical sections are accessed by one thread at a time.

47. What is the difference between a mutex and a semaphore?

##### Answer :
-  **A mutex is exclusive; a semaphore allows a limited number of threads**

##### Explanation:

> Mutexes are usually for single-thread exclusivity, while semaphores control a count of permitted accesses.

48. How do you determine whether a graph is connected?

##### Answer :
-  **Run DFS or BFS and confirm all nodes are reached**

##### Explanation:

> If every vertex is visited, the graph is connected.

49. Suppose a large file is too big to fit into memory. How would you sort it efficiently?

##### Answer :
-  **Use external sort**

##### Explanation:

> Split the file into chunks, sort each chunk in memory, and then merge the sorted runs.

50. A sequence of letters: A, C, F, J, O, ? What is the next letter?

##### Answer :
-  **K**

##### Explanation:

> The letters increase by 2, 3, 4, 5, so the next increment is 6, giving K.

---

## Practice Notes

- For technical puzzles, explain the algorithm and time complexity.
- For logic puzzles, state the assumptions clearly.
- Practice speaking your reasoning out loud as if in an interview.


