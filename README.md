# day2
#Q1. Python Program to Read a Number n And Print the Series “1+2+…..+n= “

n = int(input("Enter a Number : "))

series = []

for i in range(1,n+1):

  series.append(i)
  
  if i==n:
  
    print(i, end='')
    
  else:
  
    print(i,end=' + ')
    
print(' = ', sum(series), sep='')

#Q2.Write a Python program to count the number of even and odd numbers from
a series of numbers.

numbers = (1, 2, 3, 4, 5, 6, 7, 8, 9) # Declaring the tuple

count_odd = 0

count_even = 0

for x in numbers:

        if x % 2==0:
        
    	     count_even+=1
           
        else:
        
    	     count_odd+=1
           
print("Number of even numbers :",count_even)

print("Number of odd numbers :",count_odd)

#Q3.Write a Python program to create the multiplication table (from 1 to 10) of a
number.

n = int(input("Input a number: "))

for i in range(1,11):

   print(n,'x',i,'=',n*i)
   
#Q4.Write python program to print the pattern given below
#Note: Take input from user
#1
#2 2
#3 3 3
#4 4 4 4
#5 5 5 5 5

n=int(input('enter the number of rows'))

for i in range(1,n+1):

  for j in range(1,i+1):
  
    print(i,end='')
    
  print()


   











