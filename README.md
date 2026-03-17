# Python Assignment No.2:-
# Python Assignment Number :- 2.

#  "Chapter:-4 Lab Exercise" :-

#-------------------------------------------------------------------------------------------------    
# 1. Write a Python Program Using nested if-else statements to determine
# a students grade based on marks: Marks>=80 A:,Marks>=70:B,Marks>=60:C,Marks>=50:D,Marks<=38?
#-------------------------------------------------------------------------------------------------
# Program :-

 Python = P = 90
 Digital_Logic = D = 75
 English = E = 65
 Sociology = S = 85 
 Total_Marks = P+D+E+S
 Marks = Total_Marks / 4

 if P>=40 and D>=40 and E>=40 and S>=40:
     if Marks>=75:
         print("Grade A:Exclent")
     if Marks>=70:
         print("Grade B:Very Good")
     if Marks>=60:
         print("Grade C:Good")
     if Marks>=50:
        print("Grade D:Acceptable")
if Marks<=38:
        print("Grade E:Not Eligible")
 else:
     print("Sorry_Your are Fail") 

#.........................................................................................................    
# 2.Write a Python Program to find the largest of three numbers entered by the user using if-elif-else?
#---------------------------------------------------------------------------------------------------------
# Program :-

 Num_1 = A = int(input("Enter a number:"))
 Num_2 = B = int(input("Enter a number:"))
 Num_3 = C = int(input("Enter a number:"))
 if A>B and C<A:
     print("Num_1 is Largest:")
 elif B>A and B>C:
     print("Num_2 is Largest")
 else:
    print(" Num_3 is Largest")

#........................................................................................      
# 3. Write a Python Program to check wheather a number is prime or not using a loop? 
#----------------------------------------------------------------------------------------
# Program:-

 Num = int(input("Enter a number:"))
 if Num <= 1:
     print("Not Prime")
 else:
     Prime = True

     for i in range(2,Num):
         if Num % i == 0:
             Prime = False
             break
         if Prime:
             print("Prime")
         else:
             print("Not Prime")

#.......................................................................................     
# 4.Write a Python Program to Print all even numbers from 1 to 50 using a while loop?
#---------------------------------------------------------------------------------------   
# Program :-

 i = 1
 while i <= 50:

     if i % 2 == 0:
         print(i)
     i+=1  

#.............................................................................. 
# 5.Write a Python program to check wheather a number is palindrome or not ?
#------------------------------------------------------------------------------
# Program :-

 B = input("Enter numbers:")
 reverse = B[::-1] 
 if B == reverse:
    print(f"The given number {B} is a palindrome number")
 else:
      print(f"The given number {B} is not a palindrome number")

#........................................................................................................  
# 6.Write a Python program to print the multiplication table from to 1 to 10 using a nested for loop ?
#--------------------------------------------------------------------------------------------------------
# Program:-

 for i in range(1,11):
     print(f"Multiplication table of {i}")
     for j in range(1,11):
         print(f"{i}*{j}=" , i*j)

#================================================================      
# 7.Write a Python Program to print the square star pattern?
#----------------------------------------------------------------    
# * * * * * 
# * * * * * 
# * * * * * 
# * * * * *  
# * * * * * 
#Program :-

 Num = 5
 for i in range(0,Num):
     for j in range(Num):
         print(" * ", end=" ")
     print()   

# ------------------------------------------------------------------- 
# 8.Write a Python program to print a pattern using nested loops?
#--------------------------------------------------------------------      
# *
# * * 
# * * *
# * * * *
# * * * * *
# Program :-

 Num = 5
 for i in range(0,Num+1):
     for j in range(i):
         print("*",end="")
     print()

#====================================================================  
# 9.Write a Python program to print a pattern using nested loops?
#--------------------------------------------------------------------   
# * * * * *
# * * * *
# * * *
# * * 
# *
# Program :-

 Num = 5
 for i in range(0,Num+1):
     for j in range(i,Num):
         print("*",end=" ")
     print()  

#...............................................................................   
# 10.Write a Python Program to print a following pattern using nested loops :
#-------------------------------------------------------------------------------
# 1
# 2 2
# 3 3 3
# 4 4 4 4
# 5 5 5 5 5
 # Program :-

 Num = 5
 for i in range(1,Num+1):
     for j in range(i):
         print(i,end="")
     print()    

#----------------------------------------------------------   
# 11.Write a Python Program to print Pyramide pattern :
#----------------------------------------------------------    
#                *
#              * * *
#            * * * * *
#          * * * * * * *
#        * * * * * * * * *
# Program:-

 Num = 5 
 for i in range(1, Num+1):
     for j in range(Num-i):
         print(" ",end=" ")
     for k in range(2*i-1):
         print("*",end=" ")
     print()  

#============================================================          
# 12.Write a Python Program to print following Patterns:
#------------------------------------------------------------   
#              1
#            2 2 2
#          3 3 3 3 3
#        4 4 4 4 4 4 4 
#      5 5 5 5 5 5 5 5 5
# Program :-

 Num = 5
 for i in range(1,Num+1):
     for j in range(Num-i):
         print(" ",end=" ")
     for k in range(2*i-1):
         print(i,end=" ")
     print()        

#--------------------------------------------------------     
# 13.Write a Program to print following pattern:-
#--------------------------------------------------------   
#     * * * * *
#       * * * *
#         * * *
#           * *
#             *
# Program :-

 Num = 5
 for i in range(0, Num+1):
     for j in range(i):
         print(" ",end=" ")
     for k in range(Num-i):
         print("*", end=" ")
     print()

#------------------------------------------------------  
# Write a Program to Print The following pattern:
#------------------------------------------------------  
#                 *
#               * *
#             * * *
#           * * * *
#         * * * * *
# Program :-

 Num = 5
 for i in range(0, Num+1):
      for j in range(Num-i):
           print(" ", end=" ")
      for k in range(i):
           print("*", end=" ")
      print()            


# "Chapter:-5  Lab Exercise" :

#=============================================================================================================
# 1.Write a Python Program to create a function that takes two numbers as parameters and returns their sum :
#=============================================================================================================
# Program:-

 def Sum (a,b):
     return(a+b)
 sum = Sum(9,8)
 print(sum)

#---------------------------------------------------------------------------------------------   
# 2.Write a function that accepts a number as argument and check weather it is Prime or Not:
#=============================================================================================   
# Program:-

 def Num(a):
     if a % 2 == 0:
         print("Not Prime")
     else:
         print(" Prime")
 Check_Prime = Num(2)
 check_prime = Num(3)  

#=========================================================================================================
# 3.Write a Python Function using assert statement to check that input number is positive . If not, the 
# Program should give Error:
#=========================================================================================================
# Program:-

 Value = int(input("Enter a positive number :"))
 assert Value > 1," The number is negative"

# ..............................................................................................................
# 4.Write a Python program to create a function that accepts a string and returns the number of vowels in it :
#...............................................................................................................
# Program :-

 def count_vowels(text):
     count = 0
     vowels = "a e i o u A E I O U"
     for ch in text :
         count += 1
     return count
 string = input(" Enter a string :")
 result = count_vowels(string) 
 print(" Number of vowels :",result)

#-----------------------------------------------------------------------------------  
# 5.Write a Program to demonstrate the use of : Local variable, Global variable :
#...................................................................................  
# # Program:- 

 Num = 4 # Global Variable
 def local_function():
     Num1 = 10 # Local Variable 
     Sum = Num + Num1 # Accessing global variable in function because it can be possible due to global.
     print(Sum)
 local_function()           

#.................................................................................
# 6.Write a Recursive Function to calculate the factorial of a given number :
#.................................................................................
# Program :-

 def factorial(n):
     if n == 0 :
         return 1
     return n*factorial(n-1)
 result = factorial(5)
 print(result)

#======================================================================================
# 7.Write a Recursive Function to generate the febonacci number at position n :
#======================================================================================
# program:-

 def Fibo(num):
     if num == 1 :
         return 1
     elif num == 0 :
         return 0
     else:
         return Fibo(num-1) + Fibo(num-2)
 Result = Fibo(7)
 print(Result)    

#..............................................................................  
# 8.Write a Recursive Function to find the sum of digits of a given number :
#..............................................................................  
# Program :-

 def num(n):
     if n == 0 :
         return 0
     return n % 10 + num(int(n/10))
 Answer = num(1234)
 print(Answer) 

#----------------------------------------------------------------------------- 
# 9.Write a Recursive function to find the sum of first n natural numbers :
#----------------------------------------------------------------------------- 
# Examples:
# Input = 1234
# Output = 10
# Program:-

 def sum(n):
     return(n*(n+1))/2
 number = int(sum(5))
 print(number)

#====================================================================================
# 10.Write a Function to Calculate the Area of Circle. Take radius as parameter :
#==================================================================================== 
# Program:-

 def radius(r):
     return 3.14 * r**2
 Area = radius(8)
  print(Area)

#....................................................................................
# 11.Write a Function that takes three numbers and returns the smallest among them:
#....................................................................................
# Program:-

 def input_value(a , b , c):
      if b > a < c :
         print(f" {a} is the Smallest Number. ")
     elif a > b < c :
         print(f" {b} is the Smallest Number. ")
     else:
         print(f" {c} is the Smallest Number. ") 

 a = input(" Enter the first value :")
 b = input(" Enter the second value :")         
 c = input(" Enter the third value :")

 input_value(a , b , c)

#-----------------------------------------------------------------------------------
# 12.Write a Function that accepts a number and prints its multiplication table :
#-----------------------------------------------------------------------------------
# Program:-

 def multi_table():
     for i in range(1 , ):
         print(" Multiplication table of", i)
         for j in range(1 , 11):
             #print(i, "*" , j , i*j)
             print(f" {i}*{j} = ", i*j)    
  Multiplication_table = multi_table()          

#,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,, 
# 13.Write a recursive function to find LCM of two numbers :
# ,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,   
# Program :-

 def LCM(a , b):
     if b == 0 :
         return a
     else:
         return LCM(b , a % b)
    
 a = int(input(" Enter a Natural number :"))
 b = int(input(" Enter another Natural number :"))

 Result = LCM(a , b)
 print(" LCM is",Result)

