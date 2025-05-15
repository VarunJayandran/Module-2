# Built-in Functions -Binary Conversion Using Built-in Functions in Python
## 🎯 Aim
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## 🧠 Algorithm
Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.
## 🧾 Program
```python
a=16
print(bin(a))

```
## Output

![442780075-3d90ea4f-689b-4e69-ad4e-5a91716980a0](https://github.com/user-attachments/assets/75b044b4-4e9e-4102-8500-8906dfa29556)


## Result

Thus ,the program is executed successfully.

----

# Functions in Python: Modulo Calculator
## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## 🧠 Algorithm
1. Define a function called result that takes two arguments a and b.
2. Inside the function, compute the modulo using a % b.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the result function with the user-provided values.

## 🧾 Program
```python
def result(a,b): 
mod=a%b 
print(f"modulo is {mod}") 
a = int(input()) 
b = int(input())

```
## Output

![442782112-319fdc99-9c1a-4d0c-bb3c-6c4427328ba7](https://github.com/user-attachments/assets/bbf3f0db-37f9-4f73-a9f9-f0966d82dd24)


## Result
Thus,the program is executed suucessfully.

---

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

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
~~~python
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

~~~

##  Output
![image](https://github.com/user-attachments/assets/e5e25f69-49e8-452f-845c-d11454db239e)


## Result
Thus,the program is executed successfully.

---
