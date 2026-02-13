#  Study of While Loop in Python


##  Experiment Details

|  File |  Experiment |
|--------|--------------|
| **exp7.ipynb** | **To Study While Loop in Python** |

---

##  Aim
 To study and implement the **while loop in Python**

---

##  Theory

A **while loop** is a control flow statement that repeatedly executes a block of code **as long as a specified condition remains True**.

Unlike `for` loops, which iterate over sequences, while loops are ideal when the **number of iterations is unknown** beforehand.

### 🔹 Key Characteristics:
- Entry-controlled loop (condition checked before execution)  
- Prevents unnecessary iterations  
- Useful for validation, counting, and algorithmic problems  
- Can be controlled using `break` and `continue`  

---


#  Algorithm (Cell-wise)

---

## 🔹 Cell 1 – Print Numbers from 1 to 5
**Algorithm:**
1. Start the program.  
2. Initialize `i = 1`.  
3. Check whether `i <= 5`.  
4. If true, print `i`.  
5. Increment `i` by 1.  
6. Repeat steps 3–5 until the condition becomes false.  
7. End the program.  

---

## 🔹 Cell 2 – Print Numbers up to N
**Algorithm:**
1. Begin execution.  
2. Prompt the user to enter a value `n`.  
3. Initialize `i = 1`.  
4. While `i <= n`, print `i`.  
5. Increment `i` after each iteration.  
6. Stop when `i` exceeds `n`.  

---

## 🔹 Cell 3 – Factorial of a Number
**Algorithm:**
1. Start the program.  
2. Ask the user to input a number.  
3. Initialize `fact = 1`.  
4. While the number is greater than `0`:  
   - Multiply `fact` by the number.  
   - Decrement the number.  
5. Display the factorial.  
6. Terminate execution.  

---

## 🔹 Cell 4 – Fibonacci Series (Using Counter)
**Algorithm:**
1. Begin the program.  
2. Input the number of terms `n`.  
3. Initialize `a = 0`, `b = 1`, and counter `i = 1`.  
4. While `i <= n`:  
   - Print `a`.  
   - Compute next term `c = a + b`.  
   - Update `a = b` and `b = c`.  
   - Increment the counter.  
5. End the loop.  

---

## 🔹 Cell 5 – Fibonacci Series up to a Limit
**Algorithm:**
1. Start execution.  
2. Ask the user to enter a limit.  
3. Initialize `a = 0`, `b = 1`.  
4. While `a <= limit`:  
   - Print `a`.  
   - Update values using `a, b = b, a + b`.  
5. Stop when the limit is exceeded.  

---

## 🔹 Cell 6 – Reverse a Number
**Algorithm:**
1. Begin the program.  
2. Input a number from the user.  
3. Initialize `rev = 0`.  
4. While the number is greater than `0`:  
   - Extract the last digit using modulus (`% 10`).  
   - Append it to `rev`.  
   - Remove the last digit using integer division.  
5. Print the reversed number.  
6. End execution.  

---

## 🔹 Cell 7 – Check Palindrome Number
**Algorithm:**
1. Start the program.  
2. Accept a number from the user.  
3. Store it in a temporary variable.  
4. Reverse the number using a while loop.  
5. Compare the reversed number with the original.  
6. If equal, display `"Palindrome"`.  
7. Otherwise, display `"Not Palindrome"`.  
8. Stop execution.  

---

## 🔹 Cell 8 – Check Palindrome String (Using Loop)
**Algorithm:**
1. Begin execution.  
2. Input a string.  
3. Initialize two pointers: `i` at the start and `j` at the end.  
4. Assume the string is a palindrome.  
5. While `i < j`:  
   - Compare characters at both positions.  
   - If unequal, mark as not palindrome and break.  
   - Move pointers inward.  
6. Display the result.  
7. End the program.  

---

## 🔹 Cell 9 – Check Palindrome String (Using Slicing)
**Algorithm:**
1. Start the program.  
2. Accept a string from the user.  
3. Reverse it using slicing (`[::-1]`).  
4. Compare original and reversed strings.  
5. Display whether it is a palindrome.  
6. Terminate execution.  

---

## 🔹 Cell 10 – Count Digits in a Number
**Algorithm:**
1. Begin execution.  
2. Prompt the user for a number.  
3. Initialize `count = 0`.  
4. While the number is greater than `0`:  
   - Remove the last digit.  
   - Increment the counter.  
5. Print the total digit count.  
6. End the program.  

---

## 🔹 Cell 11 – Break Statement Example
**Algorithm:**
1. Start the program.  
2. Initialize `i = 1`.  
3. While `i < 6`, print `i`.  
4. If `i == 3`, terminate the loop using `break`.  
5. Otherwise, increment `i`.  
6. Stop execution.  

---

## 🔹 Cell 12 – Search an Element in a List
**Algorithm:**
1. Begin the program.  
2. Define a list of numbers.  
3. Ask the user to enter the element to search.  
4. Traverse the list using a while loop.  
5. If the element is found:  
   - Display its position.  
   - Exit the loop.  
6. If the loop completes without finding the element, print `"Element not found"`.  
7. End execution.  

---

## 🔹 Cell 13 – Print Only Odd Numbers (1–10)
**Algorithm:**
1. Start the program.  
2. Initialize `i = 0`.  
3. While `i < 10`:  
   - Increment `i`.  
   - If `i` is even, skip the iteration using `continue`.  
   - Otherwise, print the number.  
4. Terminate the loop.  

---

#  Conclusion

This experiment demonstrates the practical use of **while loops** in Python for repetitive and logic-driven tasks.

- While loops provide flexible iteration control.  
- They are ideal when the number of repetitions is uncertain.  
- Loop control statements improve efficiency.  
- Concepts like factorial, Fibonacci, palindrome checks, and searching build strong problem-solving skills.  
- Mastering loops is essential for writing optimized and scalable programs.
