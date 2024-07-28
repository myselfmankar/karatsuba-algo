# **Karatsuba Algorithm**

The [Karatsuba algorithm](https://en.wikipedia.org/wiki/Karatsuba_algorithm) is a divide-and-conquer approach to multiply two n-digit numbers.
It recursively divides the numbers into two halves and computes the product using three recursive multiplications instead of four.

# **Overview**

This repository contains an implementation of the Karatsuba algorithm for efficient integer multiplication.
The algorithm offers a time complexity of O($n^{1.585}$) which is significantly faster than the traditional O($n^{2}$) 
multiplication method for large numbers.

# Implementation Details 
- Language: Python 
- Time Complexity: O($n^{1.585}$)
- Space Complexity: O($n^{log n}$) due to recursion depth

# Algorithm Explanation 
The Karatsuba algorithm works by splitting each number into two halves and recursively calculating three products:
## 1. Split the numbers:
- x = $10^{n/2} x_H + x_L$
- y = $10^{n/2} y_H + y_L$  

## 2.  Compute the 3 products:
- a = $x_H . y_H$
- b = $x_L . y_L$
- d = $(x_H + x_L).(y_H + y_L) - a - b$
## 3.  Combine the result :
- result = $10^{n}.a + 10^{n/2}d + b$

By recursively applying this method, the Karatsuba algorithm achieves a faster multiplication of large numbers.

# **Reference**
 - **Wikipedia**: [Karatsuba algorithm](https://en.wikipedia.org/wiki/Karatsuba_algorithm) .
 - **Youtube** : [Explaination](https://youtu.be/JCbZayFr9RE?si=QsVCAeZV7_FEYjd8), [Example](https://youtu.be/FEzBs2rrLqs?si=YUcHFiGczk1rwcAI)
 
# **Contributing** 
We welcome contributions and suggestions to improve this project! If you have any ideas, improvements, or bug fixes, please follow these steps: 
1. Fork the repository
2. Create a new branch `git checkout -b feature-branch`.
3  Make your changes and commit them `git commit -am 'Add new feature'`.
4. Push to the branch `git push origin feature-branch`.
5. Open a pull request.


_Additionally, if you have suggestions for new features, optimizations, or improvements, please let me know by opening an issue or submitting a pull request.
Your feedback is valuable and helps me make this project better!_

# **Contact**
For any questions, suggestions, or discussions, please reach out to:
+ **_Vaishnav Mankar_**
+ **email:** _vaishnav.micro@gmail.com_
+ **GitHub:** _[myselfmankar](https://github.com/myselfmankar)_
