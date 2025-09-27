# HexSoftwares_fibonacci-generator_task1

# Task1: Fibonacci Series in Python

## 📌 Introduction
The Fibonacci series is a sequence where each number is the sum of the two preceding numbers.  
It starts with 0 and 1. The formula is:

F(n) = F(n-1) + F(n-2)

yaml
Copy code

Example series:
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...


---

## 🖥️ Code

```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        print(a, end=" ")
        a, b = b, a + b

n = int(input("Enter how many terms you want: "))
fibonacci(n)

📊 Example Output
Enter how many terms you want: 10
0 1 1 2 3 5 8 13 21 34
📝 Author
Konatham Sai Ram Chandu
📧 srchandu.konatham@gmail.com
