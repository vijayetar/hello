1.1 
### Can you change it so it can read and sum three numbers?4
  > a = int(input())  
b = int(input())  
c = int(input())  
print(a + b + c)  

1.2 
### Read the numbers b and h like this to calculate area of a right angled triangle:
  >b = int(input())  
h = int(input())  
area = 1/2*b*h  
print(area)  

1.3
### Write a program that greets the user by printing the word "Hello", a comma, the name of the user and an exclamation mark after it. See the examples below.
  >a = input()  
print('Hello, '+a+'!')  

1.4
### Write a program that reads an integer number and prints its previous and next numbers. 
  >a = int(input())  
print(f'The next number for the number {a} is {a+1}')  
print(f'The previous number for the number {a} is {a-1}')  

1.5
### N students take K apples and distribute them among each other evenly. The remaining (the indivisible) part remains in the basket. How many apples will each single student get? How many apples will remain in the basket?  

  >n = int(input())  
k = int(input())  
print(k//n)  
print(k%n)  

1.6
### Given the integer N - the number of seconds that is passed since midnight - how many full hours and full minutes are passed since midnight?  

  >a = int(input())  
h = a//3600  
s = a%3600  
m = 60*h + s//60  
print(f'{h} {m}')  

1.7
### Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.  

  >h1 = int(input())  
m1 = int(input())  
s1 = int(input())  
h2 = int(input())  
m2 = int(input())  
s2 = int(input())  
s=s2-s1  
m=(m2-m1)*60  
h=(h2-h1)*3600  
total = s+m+h  
print(total)  

2.1 
### Given a two-digit integer, print its left digit (a tens digit) and then its right digit (a ones digit).  
  >a = int(input())  
n = a//10  
r = a-(n*10)  
print(f'{n} {r}')   

2.2
### Given a two-digit integer, swap its digits and print the result. 

  >a = int(input())  
n = a//10  
r = a-(n*10)  
print(f'{r} {n}')  

2.3  
### Given an integer greater than 9, print its last two digits.
  >a = int(input())  
print(a%100)


2.4 
### Given an integer, print its tens digit.
  >a = int(input())  
cal = (a%100)//10  
print(cal)

2.5
### Given a three-digit number. Find the sum of its digits.  

  >a = int(input())  
sum = (a%10) + ((a%100)//10) + (a//100)  
print(sum)  

2.6  
### Given a positive real number, print its first digit to the right of the decimal point.

  >a = float(input())  
num = int((a*10)%10)  
print(num)  

2.7 
### A car can cover distance of N kilometers per day. How many days will it take to cover a route of length M kilometers? The program gets two numbers: N and M.  
  >n=int(input())  
m=int(input())  
if (m%n>0):  
  sum = (m//n)+1  
else:  
  sum=m//n  
print(sum)  
