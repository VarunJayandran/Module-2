# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
~~~python
a=16
print(bin(a))
~~~

## Output
![438826667-740cd71d-506b-4f8a-a0b7-5fe8554481a1](https://github.com/user-attachments/assets/3d90ea4f-689b-4e69-ad4e-5a91716980a0)

## Result
Thus ,the program is executed successfully.

---


# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
~~~python
def result(a,b): 
mod=a%b 
print(f"modulo is {mod}") 
a = int(input()) 
b = int(input())
~~~

## Output

![438832285-075c2ff7-e4b6-43d1-b6b6-187cbda60cc4](https://github.com/user-attachments/assets/319fdc99-9c1a-4d0c-bb3c-6c4427328ba7)

## Result
Thus,the program is executed suucessfully.

---

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
~~~python
a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))

~~~

## Output

![438836138-3826ebf1-9fe2-439b-b648-94fe609756f9](https://github.com/user-attachments/assets/0480622d-0dac-4105-bb4b-ffcf8e161137)

## Result

Thus,the program is executed successfully.

---

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

## 🧪 Program
```python
n=int(input())
for i in range(1,n+1):
    num=1
    for k in range(1,n-i+1):
        print(" ",end="")
    for j in range(0,i):
        if j==0 or i==0:
            num=1
        else:
            num=num*(i-j)//j
        print(num,end=" ")
    print()

```

##  Output
![image](https://github.com/user-attachments/assets/e5e25f69-49e8-452f-845c-d11454db239e)


## Result
Thus,the program is executed successfully.

---

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
~~~python
num = int(input())
rev = 0
temp = num

while temp > 0:
    digit = temp % 10  
    rev = rev * 10 + digit 
    temp //= 10 


if num == rev:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
~~~
## Output
![image](https://github.com/user-attachments/assets/382a3f23-791e-4d12-a2c2-e4be1549e244)


## Result
Thus,the program as been executed successfully

---
