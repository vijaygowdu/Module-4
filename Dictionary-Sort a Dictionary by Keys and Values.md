## EX.NO:4(A)	Dictionary-Python Program to Sort a Dictionary by Keys and Values
## AIM:
To write a python program to merge the dictionary1 with dictionary2
## ALGORITH:
Step1: Get two dictionary values

Step 2: Sort by Keys: Use sorted() function on the dictionary.

Step 3: Sort by Values: Use sorted() with a custom key: lambda item: item[1]. 

Step 4: Display the sorted dictionaries.

Step 5: End the program. 
## PROGRAM:
```
def dictionairy():
# Declaring hash function
key_value ={}
# Initializing the value
key_value[2] = 56
key_value[1] = 2
key_value[5] = 12
key_value[4] = 24
key_value[6] = 18
key_value[3] = 323

print ("Keys and Values sorted","in alphabetical order by the value")

# Note that it will sort in lexicographical order
# For mathematical way, change it to float
print(sorted(key_value.items(),
key = lambda kv:(kv[1], kv[0])))
```
## OUTPUT:
 
![image](https://github.com/user-attachments/assets/78eafe59-c908-4f3b-9967-5ceb8beb5569)

## RESULT:
Thus, the program has been successfully executed.
