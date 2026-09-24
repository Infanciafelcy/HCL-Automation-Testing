## Functional Testing(18-09-2026)
https://drive.google.com/file/d/1GJtuoedOvTW_L8lJwObWqyiN5hqrSFkk/view?usp=sharing
## EP Testing(22-09-2026)
https://drive.google.com/file/d/10CF6vx0bDR6epMuDj2Jpc0ONSsrGXIko/view?usp=sharing
## Python Programming(23-09-2026)
Write a Python program which accepts a sequence of comma separated 4 digit
binary numbers as its input and then check whether they are divisible by 5 or not.
The numbers that are divisible by 5 are to be printed in a comma separated
sequence.
Example:
0100,0011,1010,1001
Then the output should be:
1010
Solution :
```
n=input().split(",")
result=[]
for i in n:
    if int(i,2) % 5 == 0:
        result.append(i)
print(",".join(result))
```

Write a Python program that accepts a sentence and calculate the number of
letters and digits.
Suppose the following input is supplied to the program:
hello world! 123
Then, the output should be:
LETTERS 10
DIGITS 3
Solutions:
```
s = input()
letters = 0
digits = 0
for ch in s:
    if ch.isalpha():
        letters += 1
    elif ch.isdigit():
        digits += 1
print("LETTERS", letters)
print("DIGITS", digits)
```

Write a program which can compute the factorial of a given numbers.The
results should be printed in a comma-separated sequence on a single
line.Suppose the following input is supplied to the program:8
Then, the output should be:40320
Solution :
```
n = int(input())
fact = 1
for i in range(1, n + 1):
    fact = fact * i
print(fact)
```
## Manual Testing Metrics(24-09-2026)
https://1drv.ms/x/c/5C49B25A024CC059/IQC3rH90Ynl0QJMVdWL-DkRFAX2kVzSFOraKx9-pawpKQsI?e=B8g7zw

