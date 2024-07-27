# **Karatsuba Algorithm**

The Karatsuba algorithm is a divide-and-conquer approach to multiply two n-digit numbers.
It recursively divides the numbers into two halves and computes the product using three recursive multiplications instead of four.

# **Overview**

This repository contains an implementation of the Karatsuba algorithm for efficient integer multiplication.
The algorithm offers a time complexity of O($n^{1.585}$) which is significantly faster than the traditional O($n^{2}$) <br>
multiplication method for large numbers.

# Implementation Details 
- Language: Python 
- Time Complexity: O($n^{1.585}$)
- Space Complexity: O($n^{log n}$) due to recursion depth

