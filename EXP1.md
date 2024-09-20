# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 30.08.2024                                                                        
### REGISTER NUMBER : 212222040130

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
i)DO...WHILE 

```
def display(): 
  start=input("Enter a positive value for START: ") 
  end=input("Enter a positive value for END: ") 
  if start.isnumeric() and end.isnumeric():
    while True: 
      start=int(start) 
      end=int(end) 
      print(start,end=‘ ‘) 
    if start<end: 
      start+=1 
    else: 
      break 
  else: 
    print("Enter a valid positive number.")
display()
```


ii)WHILE...DO 
```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric(): 
  start=int(start) 
  end=int(end) 
  while start<end: 
    print(start) 
    start+=1 
else: 
print("Enter a valid positive number.")
```


iii) SWITCH
```
def switch(): 
  switcher={ 0:"even", 1:"odd" } 
  n=input('Enter a value for N: ')
  try: 
    n=int(n) 
    print(switcher[n%2]) 
  except ValueError: 
    print("Enter a valid number.") 
switch()
```

iv)IF ELSE
```
def compare(): 
  a=input("Enter a value for A: ") 
  b=input("Enter a value for B: ") 
  try: 
    a=int(a) 
    b=int(b) 
    if a>b: 
      print("A is greater than") 
    elif a<b: 
      print("B is greater than") 
    else: 
      print("A is equal to B") 
  except ValueError: 
    print(“Enter a valid number.”)
```

v) FOR
```
def iterate(): 
  string=input("Enter a string: ") 
  for i in string: 
    print(ord(i),end=" ") 
iterate()
```



### Output:
![exp1 (STL 1)](https://github.com/user-attachments/assets/24ce04fa-18c8-4e8a-975e-4d951162f35a)
![exp1 (STL 1)](https://github.com/user-attachments/assets/b9fa9568-5607-422a-a698-c4a39193f59d)
![exp1(stl 2 1)](https://github.com/user-attachments/assets/fe0164eb-4a86-4482-a247-8aadf3fbd29e)
![exp1(STL 2 2)](https://github.com/user-attachments/assets/70c11a9e-84bc-4736-ad44-188b501efa8d)
![exp1(STL)3](https://github.com/user-attachments/assets/3f421779-28c6-413c-9fd7-ea38bdcc53b7)
![exp1(STL)4](https://github.com/user-attachments/assets/fcb314ba-0906-4d82-beff-8b33aae98560)
![exp1(STL)5](https://github.com/user-attachments/assets/6d760026-c507-48b7-93b8-7a6405349771)






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


