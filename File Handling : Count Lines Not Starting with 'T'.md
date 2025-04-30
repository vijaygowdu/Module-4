## EX.NO:4(C)	File Handling in Python: Count Lines Not Starting with 'T
## AIM:
To Write a function in python to count the number of lines from a text file "story.txt" which is not starting with an alphabet "T".

If the file "story.txt" contains the following lines: A boy is playing there. here is a playground.

An airplane is in the sky. The sky is pink.

Alphabets and numbers are allowed in the password.
## ALGORITHM:
Step1: open the file in read mode 

Step2: iterate the words in loop

Step3: increase the count to +1 if the lines don't start with ‘T’. And print count
## PROGRAM:
```
f=open("story.txt","r")
count=0
for lines in f:
   if lines [0] not in 'T':
      count+=1
print(count)
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/5be4d23c-7520-47ce-a5af-a4c7f2e4a720)

## RESULT:
Thus, the program has been successfully executed.
