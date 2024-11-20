# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE: 17-9-24                                                                           
### REGISTER NUMBER : 212222040130
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:
```
def Palindrome(string): 
  for i in range(0, int(len(string)/2)): 
    if(string[i]!=string[len(string)-i-]): 
      return False 
 return True 
s = input() 
c = 1 
for i in s: 
  if not(i.isalpha()): 
    c = 0 
  if(c==0): 
    print("Enter a valid string") 
    answer = Palindrome(s) 
    if(answer == True): 
      print("The given string is a palindrome") 
    else: 
      print("The given string is not a palindrome")
```


### Output:

![exp6(STL)](https://github.com/user-attachments/assets/870510f7-9dfb-44b1-bf70-d5257d83608c)


### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
