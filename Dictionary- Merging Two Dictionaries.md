## EX.NO:4(B) Dictionary : Merging Two Dictionaries
## AIM:
To write a python program to merge the dictionary1 with dictionary2
## ALGORITH:
Step1: get two dictionary values

Step2: define a function merge where res= {**dict1, **dict2}

Step3: call the function and print it

## PROGRAM:
```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30}
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50}
def merge (dict1,dict2):
   res={**dict1 , **dict2}
   return res
dict3=merge(dict1,dict2)
print(dict3)
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/15b565e3-f577-4e77-8f16-08dd25486bb8)


## RESULT:
Thus, the program has been successfully executed.
