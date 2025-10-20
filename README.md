DATE : 15.10.2025
---

# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a = int(input())
print(bin(a))

```

## Output
![WhatsApp Image 2025-10-19 at 19 21 03_ce56852a](https://github.com/user-attachments/assets/2a017847-77f9-44ff-a1be-6a2a7b583590)

## Result
The program successfully converts the number 16 into its binary representation and displays the result as 0b10000 on the screen.

# Functions in Python: Modulo Calculator

## 🎯 Aim:
To write a Python program that defines a function which accepts two values and returns their *modulo* using the % operator.

## 🧠 Algorithm:
1. Define a function called result that takes two arguments a and b.
2. Inside the function, compute the modulo using a % b.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the result function with the user-provided values.

## 🧾 Program:
```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```
## Output:
<img width="662" height="311" alt="486025250-0bbe727b-0889-489b-8099-62bc66827fa3" src="https://github.com/user-attachments/assets/88cc4ac0-7b64-4b7c-8022-80ea5da3bc48" />

## Result:
The program to return two values modulo is successful.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input())
b=int(input())
f=lambda a,b:a+b
c=f(a,b)
print(c)
```
## Output
![WhatsApp Image 2025-10-19 at 21 13 47_17ad1f12](https://github.com/user-attachments/assets/24c80356-08bf-4aff-bc88-689ed4835fca)


## Result
The program successfully created lambda function to find the sum.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate *Pascal’s Triangle*, where the number of rows is provided by the user.


## 🎯 Aim

To write a Python program that generates *Pascal's Triangle* using numbers. The number of rows is accepted from the user.


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

```
n=int(input())
for i in range(n):
for k in range(n,i+1,-1):
        print(" ",end='')
        
    num=1
    for j in range(i+1):
        print(num,end=" ")
        num=num*(i-j)//(j+1)
    print()
```

## Sample Output
<img width="521" height="547" alt="image" src="https://github.com/user-attachments/assets/36271a7d-2343-4609-b0b8-044d9c5391f7" />


## Result

Thus the python program to generate Pascals's triangle has beem executed successfully.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a *palindrome* using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable num.
2. Assign the value of num to a temporary variable temp.
3. Initialize a variable rev to 0 (used to store the reversed number).
4. Use a while loop to reverse the digits:
   - While temp > 0:
     - rev = (10 * rev) + temp % 10
     - temp = temp // 10
5. After the loop, compare rev with num:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program

```
num=int(input())
temp=num
rev=0
while temp>0:
    rev=(10*rev)+temp%10
    temp=temp//10
    
if rev==num:
     print(f"The given number {num} is a Palindrome")
else:
     print(f"The given number {num} is not a palindrome")
```

## Output

<img width="984" height="253" alt="image" src="https://github.com/user-attachments/assets/71e82a71-6439-460a-afbf-3dc7fdcd5607" />


## Result
Thus the python program to check the given number is a palindrome or not has been executed successfully.
