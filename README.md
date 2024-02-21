# palindrome
# Program 1: Palindrome string
str = 'JaVaJ'  
strstr = str.casefold()  
  
# This string is reverse.  
rev = reversed(str)  
  
if list(str) == list(rev):  
   print("PALINDROME !")  
else:  
   print("NOT PALINDROME !") 


# Program 2: Palindrome string program
string=input(("Enter a letter:"))  
if(string==string[::-1]):  
      print("The letter is a palindrome")  
else:  
      print("The letter is not a palindrome")  

# Program 3: Palindrome number program using while loop
Num = int(input("Enter a value:"))  
Temp = num  
Rev = 0  
while(num > 0):  
    dig = num % 10  
    revrev = rev * 10 + dig  
    numnum = num // 10  
if(temp == rev):  
    print("This value is a palindrome number!")  
else:  
    print("This value is not a palindrome number!")  
