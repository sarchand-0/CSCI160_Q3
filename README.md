Hackerrank In a String
The time and space complexity of the provided Java program are as follows:

Time Complexity: O(n). 
The time complexity of this program is O(n), where n is the length of the input string `s`. This is because the program iterates through the input string exactly once with two pointers `i` and `j`. In the worst case, it will iterate through the entire string.

Space Complexity: O(1)
- The space complexity of this program is O(1), which is constant. The program uses a fixed amount of additional memory to store only a few variables (i, j, target string, and temporary variables for characters in `s`). The space used does not depend on the size of the input string and remains constant regardless of the input size.

Mini-Max Sum
Time Complexity: O(n log n)
Sorting the input list `arr` using `Collections.sort(arr)` has a time complexity of O(n log n), where 'n' is the number of elements in the list.Calculating the minimum sum (`min`) and maximum sum (`max`) both require iterating over the entire list, which is done in two separate loops. Each loop has a time complexity of O(n), where 'n' is the number of elements in the list. Finally Printing the results takes constant time.
Time complexity of the `miniMaxSum` function is O(n log n) + 2 * O(n), which simplifies to O(n log n) because the sorting operation dominates the overall complexity.

Space Complexity: O(n).
The main space used in this program is for storing the input list `arr`, which is of size 'n'. Therefore, the space complexity is O(n). Other variables like `min` and `max` are of type long, so they occupy a constant amount of space. The space used by the `bufferedReader` and other standard Java objects is also constant and does not depend on the input size.
The overall space complexity is O(n) due to the input list `arr`.



