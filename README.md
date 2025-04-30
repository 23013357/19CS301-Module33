# 19CS301-Module33
Exp.No:3(a)	STRING- STRING AND REMOVE
### AIM
To write a python function that accepts a string and removes the nth index value from the string.
### ALGORITHM
Step 1:	 Start the program.

Step 2:	 Define a function remove(s) that takes a string s as input.

Step 3:	 Inside the function, initialize an empty string c to store the result.

Step 4:	 Input an integer n (the index of the character to be removed).

Step 5:	 Loop through each character in the string using index i from 0 to len(s) - 1:

Step 6:	 If i is not equal to n, append s[i] to the string c.

Step 7:	 After the loop, print the string c, which now excludes the character at index n.

Step 8:	 End the function.

### PROGRAM
```
def remove(s):
    c=""
    n=int(input())
    for i in range(len(s)):
        if i!=n:
            c=c+s[i]
    print(c)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/ab789972-0bcc-4de6-a234-f80f5209ed92)

### RESULT
Thus the python program of string and remove is implemented and executed successfully.


Exp.No:3(b)	REGEX-PATTERN MATCHING USING REGEX

### AIM
To write a Python program that matches a string that has an a followed by two to three 'b'.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept a string str1 from the user.

Step 3:	 Define a regular expression pattern as r"[a]+b{2,3}".

Step 4:	 Use the re.match() function to check if the string str1 matches the given pattern. If the string str1 matches the pattern, proceed to step 5. Else If the string str1 does not 
          match the pattern, proceed to step 6.

Step 5:	 Print "Found a match!" if the string matches the pattern.

Step 6:	 Print "Not matched!" if the string does not match the pattern.

Step 7:	 Terminate the program.

### PROGRAM
```import re
str1=input()
pattern=r"[a]+b{2,3}"
if re.match(pattern,str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/b473b268-4127-4409-9985-e43d47b02847)

### RESULT
Thus the python program for pattern matching using regular expression was  implemented and executed successfully.

Exp.No:3(c)	LIST- EVEN NUMBERS LIST

### AIM
To write a python function that accepts N and to create a list with even numbers up to N.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer a.

Step 3:	 Create an empty list l.

Step 4:	In For Loop, Iterate through the numbers from 1 to a-1.For each number i, check if i is even: If i % 2 == 0, append i to the list l.

Step 5:	 Print the list l which contains all even numbers from 1 to a-1.

Step 6:	 Terminate the program.
### PROGRAM
```def createlist(a):
    l=[]
    for i in range(1,a):
        if (i%2==0):
            l.append(i)
    print(l)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/a21369b0-1967-4362-b91f-84bb82becbcd)

### RESULT
Thus the python program for printing a list with even numbers up to n, was implemented and executed successfully.

Exp.No:3(d)	TUPLES- A TUPLE WITH MULTIPLES OF 5
### AIM
To write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer N from the user.

Step 3:	 Define an empty tuple multiples_of_5.

Step 4:	 Loop through the numbers starting from 5, up to N-1 (not including N), with a step size of 5 For each value of i, add i to the tuple multiples_of_5.

Step 5:	 Return the multiples_of_5 tuple.

Step 6:	 print the resultant tuple.

Step 7:	 Terminate the program.
### PROGRAM
```
def create_tuple(N):
    multiples_of_5 = tuple(i for i in range(5, N, 5))
    return multiples_of_5
N = int(input())
result = create_tuple(N)
print(f"{result}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/a16820ca-d669-4520-b141-c4e0a836c910)


 
### RESULT
Thus the python program for printing a tuple with numbers that are multiples of 5 up to n, was implemented and executed successfully.

Exp.No:3(e)	SEB- STRING SLICING
### AIM
To write a python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Take a slice of input_string starting from index 2 up to index 10.

Step 3:	 Reverse the substring.

Step 4:	 slice the reversed string, extracting every second character, starting from the first.

Step 5:	 Print the sliced string in the above step.

Step 6:	 Terminate the program.
### PROGRAM
```
def slice(input_string):
    substring = input_string[2:10:]
    reversed_substring = substring[::-1]
    print(f"The reversed string is '{reversed_substring[::2]}'")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/1c3e5d33-4525-44e9-93c4-3431af135a04)

### RESULT
Thus the python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string was implemented and executed successfully.









