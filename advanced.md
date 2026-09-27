# Advanced Puzzles

## 50 Practice Questions with Answers and Explanations

1. Classic bulb puzzle: A building has 3 floors. On the top floor are 3 bulbs, and on the ground floor are 3 switches. You may go to the top floor only once. How do you determine which switch controls each bulb?> *Answer:* Turn switch 1 on for a while, then off. Turn switch 2 on and go upstairs. The lit bulb is switch 2, the warm bulb is switch 1, and the remaining bulb is switch 3.> *Explanation:* The key is the difference between a bulb that is currently lit and a bulb that is merely warm.

2. You have a 5-liter jug and a 3-liter jug and need exactly 1 liter. How do you do it?> *Answer:* Fill the 5-liter jug, pour into the 3-liter jug until it is full, leaving 2 liters. Empty the 3-liter jug, pour the 2 liters into it, refill the 5-liter jug, and pour into the 3-liter jug until it is full. Exactly 1 liter remains in the 5-liter jug.> *Explanation:* This is the classic jug-transfer method for measuring a target volume.

3. A deck of 52 cards is shuffled. What is the probability the first card is a king or the second card is a queen?> *Answer:* 4/52 + 4/52 âˆ’ (4/52 Ã— 4/51) â‰ˆ 15.7%.> *Explanation:* Use inclusion-exclusion because the two events may overlap.

4. Youâ€™re in a 2D maze and you can only move east or north. How many unique paths are there from one corner to the opposite?> *Answer:* The number of paths is C(m+n, m), where m and n are the dimensions.> *Explanation:* Each path is a sequence of east and north moves; the count is a binomial coefficient.

5. What is the maximum number of regions formed by n lines in general position?> *Answer:* n(n+1)/2 + 1.> *Explanation:* Each new line intersects all previous lines at distinct points and splits the plane into one more region than before.

6. An array contains duplicate numbers. How do you find the repeated element in O(n) time without extra space?> *Answer:* Use the Floyd cycle-finding method or a bitwise approach depending on the constraints.> *Explanation:* In a list where numbers repeat, cycle detection or a mathematical property can find the duplicate in linear time without additional storage.

7. In a binary tree, how do you determine if it is balanced?> *Answer:* Check the height of each subtree recursively and ensure the height difference is at most 1.> *Explanation:* A balanced tree keeps the left and right subtree heights close together.

8. Given a graph with positive weights, how do you find the shortest path from a source to all nodes?> *Answer:* Use Dijkstraâ€™s algorithm.> *Explanation:* It works by always choosing the smallest known distance and relaxing neighbors.

9. How do you detect a cycle in an undirected graph?> *Answer:* Run DFS and track visited nodes with a parent pointer.> *Explanation:* If you revisit a node that is not the parent, there is a cycle.

10. How many times does the digit 7 appear from 1 to 1000?> *Answer:* 300.> *Explanation:* The digit appears 20 times in each hundred block, plus 100 times in the 700â€“799 block.

11. A function is called recursively with n decreasing by 1. What is its time complexity?> *Answer:* O(n).> *Explanation:* Each call reduces the problem by one, creating a chain of length n.

12. A process runs 10 tasks concurrently. What is the deadlock condition, and how do you prevent it?> *Answer:* Deadlock occurs when processes wait on resources in a cycle. Prevent it using lock ordering, timeout, or resource allocation discipline.> *Explanation:* A deadlock exists when no process can proceed because each is waiting on another.

13. A system has 3 servers and one request can be processed by any server. How do you maximize throughput while maintaining fault tolerance?> *Answer:* Put a load balancer in front of replicated servers and health checks.> *Explanation:* This distributes load evenly and keeps service running if one server fails.

14. In a distributed system, what is the difference between consistency, availability, and partition tolerance?> *Answer:* Consistency means all nodes see the same data; availability means the system responds; partition tolerance means the system keeps working when network partitions happen.> *Explanation:* CAP says you can only guarantee at most two of the three at the same time.

15. There are 100 prisoners and 100 boxes, each containing a prisonerâ€™s number. How can they maximize the chance to find their own number?> *Answer:* Each prisoner opens the box matching their number and continues following the chain until they find their own number or fail after 50 attempts.> *Explanation:* This strategy succeeds with high probability by exploiting the permutation structure of the boxes.

16. If 8 people sit around a round table, how many unique circular arrangements are there?> *Answer:* 7! = 5040.> *Explanation:* Rotations are considered the same in a circle, so divide by 8.

17. You have a function that returns the maximum element in an array. The array is unsorted. What is the best possible complexity?> *Answer:* O(n).> *Explanation:* In the worst case, every item must be inspected to know the maximum.

18. A number is chosen randomly from 1 to 100. What is the probability it is divisible by 3 or 5?> *Answer:* 47/100.> *Explanation:* There are 33 multiples of 3, 20 multiples of 5, and 6 overlap values, giving 47 unique numbers.

19. A list is sorted in ascending order. What is the complexity of binary search?> *Answer:* O(log n).> *Explanation:* Each step halves the remaining search space.

20. A staircase can be climbed in 1 or 2 steps. How many ways can you climb 20 steps?> *Answer:* 10946.> *Explanation:* This is the Fibonacci recurrence: f(n) = f(nâˆ’1) + f(nâˆ’2).

21. How many ways can you arrange 5 books on a shelf?> *Answer:* 5! = 120.> *Explanation:* A shelf arrangement is a permutation of five distinct books.

22. If a coin is flipped 10 times, what is the probability of getting exactly 5 heads?> *Answer:* C(10,5)/2^10 = 252/1024 â‰ˆ 24.6%.> *Explanation:* We choose 5 positions for heads out of 10 flips and divide by all possible outcomes.

23. A string is a palindrome if reversed equals itself. How do you check this efficiently?> *Answer:* Compare the first and last characters, moving inward.> *Explanation:* This approach runs in O(n) time and O(1) extra space.

24. In a priority queue, what is the time complexity of extracting the maximum element?> *Answer:* O(log n).> *Explanation:* A priority queue is commonly implemented with a heap, and extraction takes logarithmic time.

25. There are 50 red balls and 50 blue balls. You pick 2 without replacement. What is the probability both are red?> *Answer:* C(50,2)/C(100,2) â‰ˆ 49.5%.> *Explanation:* You choose 2 red balls out of 50 and divide by all possible 2-ball combinations.

26. How do you find the median of an unsorted array in linear time?> *Answer:* Use a linear-time selection algorithm such as median-of-medians.> *Explanation:* This avoids sorting the entire array and still finds the middle element.

27. Given two linked lists, how do you detect if they intersect?> *Answer:* Use two pointers traversing the lists and adjust for different lengths.> *Explanation:* When the pointers meet, the lists intersect at that node.

28. A hash map has collisions. How do you resolve them?> *Answer:* Use separate chaining or open addressing.> *Explanation:* Both methods preserve lookup behavior even when multiple keys hash to the same bucket.

29. A sorted array has duplicates. How do you find the first index of a target in O(log n)?> *Answer:* Use binary search on the leftmost matching index.> *Explanation:* You keep searching left while the value is equal to the target.

30. A binary search tree is not balanced. What happens to insertion and lookup times?> *Answer:* They degrade to O(n) in the worst case.> *Explanation:* An unbalanced BST can behave like a linked list.

31. Suppose you have a stream of data and need to return the top K frequent items. How do you do it efficiently?> *Answer:* Use a hash map for counts and a min-heap of size K.> *Explanation:* This keeps the most frequent items without scanning all data repeatedly.

32. In a system with 3 processes competing for 2 resources, how can a deadlock arise?> *Answer:* Process A holds resource X and waits for Y while process B holds Y and waits for X.> *Explanation:* This creates a circular wait, which is one of the conditions for deadlock.

33. What is the difference between a stack and a queue?> *Answer:* A stack is LIFO and a queue is FIFO.> *Explanation:* The ordering of insertion and removal is the defining difference.

34. Explain the CAP theorem in one sentence.> *Answer:* In a distributed system, you can have at most two of consistency, availability, and partition tolerance.> *Explanation:* Partition tolerance is often required in real systems, so teams usually choose between consistency and availability.

35. If a function runs in O(log n) time, how does doubling the input affect runtime?> *Answer:* It adds only a constant amount of time.> *Explanation:* Logarithmic growth is very slow; doubling input increases the runtime by a fixed increment.

36. How would you design a rate limiter for an API?> *Answer:* Use a token bucket or leaky bucket algorithm.> *Explanation:* This limits requests over a time window and prevents overload.

37. How do you detect whether a binary tree is a valid BST?> *Answer:* Perform an inorder traversal and check that values are strictly increasing or maintain min/max bounds.> *Explanation:* In-order traversal of a BST should produce sorted values.

38. A string contains parentheses. How do you check if the sequence is balanced?> *Answer:* Use a stack and push opening brackets, popping on closing brackets.> *Explanation:* The stack ensures every opening bracket has a matching closing bracket in the proper order.

39. What is the time complexity of mergesort?> *Answer:* O(n log n).> *Explanation:* It divides the array into halves and merges sorted halves recursively.

40. If 20% of the population has some trait and a test is 90% accurate, what is the probability a positive test result is actually correct?> *Answer:* About 33.3% under the standard assumptions used in Bayesâ€™ theorem.> *Explanation:* A large number of positives come from a small base rate, so accuracy alone does not guarantee correctness.

41. A lock has 3 wheels with digits 0â€“9. How many possible combinations are there?> *Answer:* 1000.> *Explanation:* Each wheel has 10 choices, so 10 Ã— 10 Ã— 10 = 1000.

42. A carousel rotates by 90 degrees every second. How do you compute its position after 10 seconds?> *Answer:* 10 Ã— 90Â° = 900Â°, which is equivalent to 180Â° after modulo 360Â°.> *Explanation:* Rotations are periodic every 360Â°, so angle reduction is necessary.

43. You have a graph with 100 vertices and 200 edges. Is it guaranteed to have a cycle?> *Answer:* Yes, if the graph is connected, it is likely to contain at least one cycle.> *Explanation:* A connected graph with 100 vertices and 200 edges has more than enough edges to create cycles.

44. If a system has a 1-second timeout and 5 concurrent requests, how would you prevent a thundering herd?> *Answer:* Use jittered retries and a shared cache or rate limiter.> *Explanation:* Staggering retries prevents a synchronized retry storm after a timeout.

45. How do you find the longest increasing subsequence in an array?> *Answer:* Use patience sorting or dynamic programming.> *Explanation:* The LIS is the longest sequence of increasing values in order, not necessarily contiguous.

46. You receive an array where every number appears twice except one. How do you find the unique number?> *Answer:* Use XOR on all numbers.> *Explanation:* XOR cancels identical values and leaves only the unique one.

47. A process can access the same memory from multiple threads. How do you prevent race conditions?> *Answer:* Use mutexes, semaphores, or atomic operations.> *Explanation:* Synchronization ensures that critical sections are accessed by one thread at a time.

48. What is the difference between a mutex and a semaphore?> *Answer:* A mutex allows one thread exclusive access; a semaphore allows a limited number of threads to access a resource simultaneously.> *Explanation:* Both provide coordination, but semaphores are more general.

49. How do you determine whether a graph is connected?> *Answer:* Run DFS or BFS from one node and check whether all nodes are reached.> *Explanation:* If every vertex is visited, the graph is connected.

50. Suppose a large file is too big to fit into memory. How would you sort it efficiently?> *Answer:* Use external sort: divide the file into chunks, sort each chunk in memory, then merge the sorted runs.> *Explanation:* This works because only manageable pieces need to be held in memory at any one time.

---

## Practice Notes

- For technical puzzles, explain the algorithm and time complexity.
- For logic puzzles, state the assumptions clearly.
- Practice speaking your reasoning out loud as if in an interview.


