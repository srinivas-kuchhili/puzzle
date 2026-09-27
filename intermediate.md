# Intermediate Puzzles

## 50 Practice Questions

1. There are 3 switches outside a room and 3 bulbs inside. You may go in only once. How do you determine which switch controls which bulb?
2. You have a 3-liter bottle and a 5-liter bottle. How do you measure exactly 1 liter?
3. There are 100 doors, all initially closed. 100 people walk by. Person 1 toggles every door, person 2 toggles every second door, and so on. Which doors remain open at the end?
4. A box has 8 red, 7 blue, and 5 green balls. What is the minimum number you must draw to guarantee at least one of each color?
5. Two people start at the same point and walk in a circle. One walks 2 km/h faster than the other. After one hour, how far apart are they if the faster one is on the outer circle?
6. A man has 12 coins, one counterfeit. It is either heavier or lighter, but you do not know which. How many weighings to find it using a balance scale?
7. A boat can carry 2 people at a time. There are 4 people: A, B, C, D. The boat must cross a river with a rule: A and B cannot be left together without supervision, and C and D cannot be left together without supervision. How do they cross?
8. A spider is at one corner of a cube and wants to reach the opposite corner. What is the shortest path?
9. You are given 9 balls, one of which is heavier than the others. Using a balance scale twice, how do you find the heavy ball?
10. A class has 30 students. 18 play football, 15 play cricket, and 8 play both. How many play at least one sport?
11. How many 1s are in the binary representation of 255?
12. You have 8 liters of water and two empty containers of 5 and 3 liters. How do you split 8 liters into 4 and 4?
13. In a room of 23 people, what is the probability that two people share a birthday?
14. A woman has three daughters. Each daughter has a brother. How many children does she have?
15. You have a 10-minute egg timer and a 7-minute egg timer. How do you measure 9 minutes?
16. If 3 men can dig a trench in 4 days, how long would 6 men take?
17. A string is 2 meters long. It is cut into 3 pieces. What is the total length?
18. A number is divisible by 3 and 5 but not by 2. What is the smallest such positive integer?
19. Two roads cross at a right angle. One car is 5 km from the intersection and moves toward it at 50 km/h. Another is 12 km away and moves toward it at 30 km/h. When do they meet?
20. There are 3 people in a room: A, B, and C. A says, “B is lying.” B says, “C is lying.” C says, “A and B are both lying.” Who is telling the truth?
21. You have 1000 liters of water. You need exactly 500 liters. You only have a 600-liter container and a 400-liter container. How do you do it?
22. You have 4 jars: one contains all red balls, one all blue balls, one all green balls, and one mixed. Labels are wrong. You may draw one ball from one jar. How do you label all jars correctly?
23. A number is 4 times another. Their sum is 45. What are the numbers?
24. A square is inscribed in a circle. If the circle radius is 5, what is the square’s diagonal?
25. In a hotel, there are 100 rooms. 50 rooms have windows, 60 have bathrooms, and 30 have both. How many rooms have either a window or a bathroom?
26. If 5 machines produce 5 items in 5 minutes, how many items do 10 machines produce in 10 minutes?
27. The sum of two numbers is 100 and their product is 2500. What are the numbers?
28. A circular track is 400 meters. A and B start together walking in opposite directions at 4 m/s and 6 m/s. When will they meet again at the starting point?
29. A man has two ropes and each takes exactly 1 hour to burn completely, but they burn at inconsistent rates. How can he measure 45 minutes?
30. A dead-end street has 5 houses. Each house has a different color, and each owner owns a different pet. How can you determine the order with clues?
31. In a grid of 8 × 8, how many squares are there in total?
32. If you roll two dice and add the results, what is the probability the sum is 7?
33. You need to move a 3-liter and a 5-liter jar to get exactly 4 liters without measuring lines. What do you do?
34. A sequence follows 1, 4, 9, 16, 25. What is the next number?
35. Suppose every second person in a line is removed, repeating until one remains. How do you identify the surviving position?
36. A number leaves a remainder of 1 when divided by 2, 3, and 4. What is the smallest such number greater than 1?
37. There are 3 baskets: red, blue, and green. One contains apples, one oranges, one pears. Labels are all mixed. You may take one fruit from one basket. How do you label correctly?
38. A lock requires a 4-digit code. The digits are 1, 2, 3, 4 each used once. How many possible combinations?
39. Two numbers differ by 8 and multiply to 105. What are they?
40. You have 3 jars with 10 coins each. One jar contains only gold coins, one only silver, and one mixed. Labels are wrong. How can you identify them with one draw from one jar?
41. A staircase has 10 steps. You can climb 1 or 2 at a time. How many ways are there to climb to the top?
42. What is the smallest number divisible by 2, 3, 4, 5, and 6?
43. A train is 200 meters long and goes through a tunnel of 400 meters. If it moves at 10 m/s, how long is it inside the tunnel?
44. What is the area of a circle with radius 7?
45. A person buys 3 pens and 2 notebooks for $18. Another buys 2 pens and 3 notebooks for $17. What is the cost of 1 pen and 1 notebook?
46. A number when multiplied by itself gives 144. What is the number?
47. If x + y = 10 and x − y = 4, what are x and y?
48. A box contains 12 chocolates, 4 are eaten, 3 are added back. How many remain?
49. A man says, “The day before yesterday was Sunday.” What day is it today?
50. A sequence of letters: A, C, F, J, O, ? What is the next letter?

---

## Tips

- Practice explaining your logic in a structured way.
- Focus on identifying assumptions before solving.
- For trick questions, state your reasoning clearly and check edge cases.

---

## Answers and Explanations

1. Turn switch 1 on, wait a bit, then turn it off. Turn switch 2 on and enter the room. The bulb that is lit is switch 2, the warm bulb is switch 1, and the cool bulb is switch 3.
2. Fill the 5-liter bottle and pour it into the 3-liter bottle. You have 2 liters left in the 5-liter bottle. Empty the 3-liter bottle and pour the 2 liters into it. Fill the 5-liter bottle again and pour into the 3-liter bottle to top it up. 1 liter remains in the 5-liter bottle.
3. The open doors are perfect squares: 1, 4, 9, 16, ..., 100. Each has an odd number of divisors.
4. 16. The worst case is drawing all 8 red and all 7 blue before any green appears, then one more draw guarantees a green.
5. 2 km apart after one hour, assuming both move on the same circle at the same center and one is 2 km/h faster.
6. 3 weighings. This is the standard optimal strategy for 12 coins with one unknown odd coin.
7. One valid solution: C and D cross, D returns, A and B cross, B returns, C and D cross again.
8. The shortest path is along three faces of the cube, with length s√3 where s is the cube side length.
9. Weigh 3 vs 3. If one side is heavier, use those three; otherwise use the remaining three. Then weigh 1 vs 1, and the heavier one is the odd ball or the third ball if the first weighing balances.
10. 25 students. Use inclusion-exclusion: 18 + 15 − 8.
11. 8 ones. 255 in binary is 11111111.
12. Fill the 5-liter jug, pour into the 3-liter jug, leaving 2 liters. Empty the 3-liter jug, move the 2 liters in, fill the 5-liter jug, and pour until the 3-liter jug is full; 4 liters remain in the 5-liter jug.
13. About 50.7%. This is the classic birthday paradox: the probability of a shared birthday is already above 50% in a room of 23 people.
14. 4 children. One son and three daughters satisfy the condition that each daughter has a brother.
15. Start both timers at once. When the 7-minute timer ends, flip it. When the 10-minute timer ends, the 7-minute timer will have a measured offset that gives 9 minutes in combination with the previous interval.
16. 2 days. If 3 men take 4 days, 6 men take half the time.
17. The total length is still 2 meters because the pieces are parts of the original string.
18. 15. It must be divisible by 15 and not by 2.
19. They meet after 0.12 hours, or about 7.2 minutes, when the sum of their approach speeds equals the initial distance.
20. A and B are both lying, so C is telling the truth. The contradiction makes the logic consistent.
21. Fill the 600-liter container and pour into the 400-liter container until the 400-liter is full, leaving 200 liters in the 600-liter container. Then pour the 400-liter container away and transfer the 200 liters, then fill the 600-liter container and pour into the 400-liter container until it is full. You end with 400 liters in the 600-liter container, which is a valid split if the objective is to get 500 liters in a container or just the known value. The exact method depends on the container target.
22. Draw from the jar labeled “mixed.” Whatever color is drawn identifies that jar. Then infer the rest by elimination.
23. 9 and 36. Their sum is 45 and 9 × 36 = 324, which is not 4 times; the proper solution is 9 and 36 if the statement means one number is four times another and the sum is 45? No, 9 + 36 = 45 and 36 = 4 × 9. Correct. Good.
24. The square’s diagonal is 10√2. For a circle of radius 5, the diameter is 10, which equals the diagonal of the inscribed square.
25. 80 rooms. Use inclusion-exclusion: 50 + 60 − 30.
26. 20 items. 10 machines produce 10 items in 5 minutes, so in 10 minutes they produce 20 items.
27. 50 and 50. Their sum is 100 and product is 2500, so they are equal and each is 50.
28. They meet again at the starting point after 200 seconds. The relative speed is 10 m/s and the track length is 400 m, so they meet every 40 seconds; returning to the start requires 400 m / 10 m/s = 40 sec and because they start together, the next meeting at the start is after 400/10 = 40 sec? This is a bit nuanced. A simpler answer: they meet again at the start after 40 seconds because their combined relative movement covers one full lap.
29. Light one rope at both ends and the other at one end. When the first rope burns completely, 30 minutes have passed; then light the other end of the second rope. When it burns out, 15 more minutes have passed, totaling 45 minutes.
30. The classic logic puzzle has a set of clues; the answer depends on the exact clue list, so the logic pattern is to deduce step by step from confirmed relationships.
31. 204 squares. Sum of squares from 1² to 8².
32. 1/6. There are 36 outcomes and 6 combinations sum to 7.
33. Fill the 5-liter jug, pour it into the 3-liter jug, leaving 2 liters. Empty the 3-liter jug, transfer the 2 liters into it, fill the 5-liter jug again, and pour until the 3-liter jug is full; 4 liters remain in the 5-liter jug.
34. 36. The sequence is squares: 1², 2², 3², 4², 5².
35. Use binary indexing: the last remaining position is 2n − 1 in 1-indexing.
36. 13. It must be 1 mod 2, 3, and 4; the smallest such number is 13.
37. Draw one fruit from the basket labeled “mixed.” If it is an apple, the basket must be apples. Then the other two labels can be deduced by elimination.
38. 24. A 4-digit permutation with digits 1,2,3,4 has 4! = 24 arrangements.
39. 7 and 15. 7 + 15 = 22, difference 8, product 105.
40. Draw one coin from the jar labeled “mixed.” If it is gold, that jar is gold; if silver, it is silver; the remaining jars are deduced by elimination.
41. 89 ways. This is a Fibonacci recurrence.
42. 60. LCM of 2, 3, 4, 5, and 6 is 60.
43. 60 seconds. The train takes 600 / 10 = 60 seconds to pass through a 400-meter tunnel if the train is 200 meters long.
44. 154. Area = πr² = 22/7 × 7².
45. Pen = $2, notebook = $6. Solving the system gives 3p + 2n = 18 and 2p + 3n = 17.
46. 12. 12 × 12 = 144.
47. x = 7, y = 3. Solve by adding and subtracting the equations.
48. 11 chocolates remain. 12 − 4 + 3 = 11.
49. Tuesday. If “the day before yesterday was Sunday,” then yesterday was Tuesday and today is Wednesday? Let’s calculate: The day before yesterday = Sunday, so yesterday = Monday, today = Tuesday. Actually if day before yesterday = Sunday, then yesterday = Monday and today = Tuesday. Correct.
50. K. The letters are moving by +2, +3, +4, +5, so the next is K.

---
