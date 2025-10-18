# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To convert a decimal number into its binary equivalent using Python’s built-in function.

## 🧠 Algorithm
1.Start

2.Take input from the user for a decimal number.

3.Use Python’s built-in bin() function to convert the decimal number to binary.

          bin(number) returns a string representing the binary value prefixed with 0b.

4.Print the binary result.

5.End

## 🧾 Program

```
def decimal_to_binary(decimal_number):
    return bin(decimal_number)
decimal_number=int(input())
binary_number=decimal_to_binary(decimal_number)
print(binary_number)
```

## Output
<img width="767" height="261" alt="image" src="https://github.com/user-attachments/assets/a55dac95-8c29-439b-8b93-b4c97a9f5405" />


## Result
The program successfully converts any given decimal number into its binary form.
