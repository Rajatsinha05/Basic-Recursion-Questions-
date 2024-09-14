
### Recursion Questions 

#### 1. **Factorial of a Number**
   - **Instruction**: Write a recursive function to calculate the factorial of a given non-negative integer `n`. The factorial of `n` is defined as `n! = n * (n-1) * (n-2) * ... * 1`, and `0! = 1`.
   - **Sample Input and Output**:
     - Input: `5`
     - Output: `120`
     - Input: `0`
     - Output: `1`
     - Input: `3`
     - Output: `6`
   - **Explanation**: The function multiplies the current number `n` by the factorial of `n-1` until `n` is 0.

#### 2. **Sum of Natural Numbers**
   - **Instruction**: Write a recursive function to find the sum of the first `n` natural numbers. The sum of the first `n` natural numbers is `n + (n-1) + (n-2) + ... + 1`.
   - **Sample Input and Output**:
     - Input: `5`
     - Output: `15`
     - Input: `3`
     - Output: `6`
     - Input: `0`
     - Output: `0`
   - **Explanation**: The function adds the current number `n` to the sum of the numbers from `1` to `n-1`.

#### 3. **Fibonacci Series**
   - **Instruction**: Write a recursive function to find the `n`th Fibonacci number. The Fibonacci sequence is defined as `F(0) = 0`, `F(1) = 1`, and `F(n) = F(n-1) + F(n-2)` for `n > 1`.
   - **Sample Input and Output**:
     - Input: `5`
     - Output: `5`
     - Input: `0`
     - Output: `0`
     - Input: `7`
     - Output: `13`
   - **Explanation**: The function returns the sum of the previous two Fibonacci numbers until it reaches the base cases `0` and `1`.

#### 4. **Reverse a String**
   - **Instruction**: Write a recursive function to reverse a given string.
   - **Sample Input and Output**:
     - Input: `"hello"`
     - Output: `"olleh"`
     - Input: `"abcd"`
     - Output: `"dcba"`
     - Input: `"recursion"`
     - Output: `"noisrucer"`
   - **Explanation**: The function takes the last character of the string and appends it to the reverse of the remaining substring.

#### 5. **Sum of Digits**
   - **Instruction**: Write a recursive function to calculate the sum of the digits of a given non-negative integer.
   - **Sample Input and Output**:
     - Input: `123`
     - Output: `6`
     - Input: `456`
     - Output: `15`
     - Input: `789`
     - Output: `24`
   - **Explanation**: The function adds the last digit of the number to the sum of the digits of the remaining number.

#### 6. **Power of a Number**
   - **Instruction**: Write a recursive function to calculate `x` raised to the power of `n` (`x^n`).
   - **Sample Input and Output**:
     - Input: `2, 3`
     - Output: `8`
     - Input: `5, 0`
     - Output: `1`
     - Input: `3, 4`
     - Output: `81`
   - **Explanation**: The function multiplies `x` by the result of `x` raised to the power of `n-1` until `n` is `0`.

#### 7. **Count Occurrences of a Character**
   - **Instruction**: Write a recursive function to count the occurrences of a specific character in a given string.
   - **Sample Input and Output**:
     - Input: `"hello", 'l'`
     - Output: `2`
     - Input: `"recursion", 'r'`
     - Output: `2`
     - Input: `"apple", 'p'`
     - Output: `2`
   - **Explanation**: The function checks if the first character of the string matches the given character, adds `1` if true, and proceeds to the next character.

#### 8. **Check if a String is Palindrome**
   - **Instruction**: Write a recursive function to check if a given string is a palindrome (reads the same forward and backward).
   - **Sample Input and Output**:
     - Input: `"racecar"`
     - Output: `true`
     - Input: `"hello"`
     - Output: `false`
     - Input: `"madam"`
     - Output: `true`
   - **Explanation**: The function compares the first and last characters of the string and recursively checks the substring excluding those characters.

#### 9. **Greatest Common Divisor (GCD)**
   - **Instruction**: Write a recursive function to find the GCD of two non-negative integers using the Euclidean algorithm.
   - **Sample Input and Output**:
     - Input: `48, 18`
     - Output: `6`
     - Input: `56, 98`
     - Output: `14`
     - Input: `101, 10`
     - Output: `1`
   - **Explanation**: The function finds the GCD by repeatedly subtracting the smaller number from the larger or using modulus until one of the numbers becomes `0`.

#### 10. **Find Minimum in an Array**
   - **Instruction**: Write a recursive function to find the minimum element in an array of integers.
   - **Sample Input and Output**:
     - Input: `[3, 1, 4, 1, 5, 9]`
     - Output: `1`
     - Input: `[10, 20, 5, 8, 3]`
     - Output: `3`
     - Input: `[7, 6, 2, 8, 4]`
     - Output: `2`
   - **Explanation**: The function compares the first element with the minimum of the rest of the array recursively to find the smallest value.

#### 11. **Sum of Array Elements**
   - **Instruction**: Write a recursive function to find the sum of all elements in an array.
   - **Sample Input and Output**:
     - Input: `[1, 2, 3, 4, 5]`
     - Output: `15`
     - Input: `[10, 20, 30]`
     - Output: `60`
     - Input: `[7, -2, 3]`
     - Output: `8`
   - **Explanation**: The function adds the first element to the sum of the remaining elements until the array is empty.

#### 12. **Reverse an Array**
   - **Instruction**: Write a recursive function to reverse an array.
   - **Sample Input and Output**:
     - Input: `[1, 2, 3, 4]`
     - Output: `[4, 3, 2, 1]`
     - Input: `[10, 20, 30]`
     - Output: `[30, 20, 10]`
     - Input: `[7, 6, 5]`
     - Output: `[5, 6, 7]`
   - **Explanation**: The function swaps the first and last elements, then recursively calls itself on the subarray excluding the swapped elements.

#### 13. **Count Occurrences in Array**
   - **Instruction**: Write a recursive function to count the occurrences of a given element in an array.
   - **Sample Input and Output**:
     - Input: `[1, 2, 2, 3, 2], 2`
     - Output: `3`
     - Input: `[4, 5, 6, 5, 4], 4`
     - Output: `2`
     - Input: `[7, 8, 9, 7, 9], 7`
     - Output: `2`
   - **Explanation**: The function checks each element, increments the count if it matches the given element, and recursively checks the rest of the array.
