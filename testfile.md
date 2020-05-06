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

2.8  
### Given a year (as a positive integer), find the respective number of the century. 
  >a = int(input()) 
b = a//100  
c = (b*100)  
d = c+1  
e=c-99  
if (a>e and a<d):  
  print(b)  
else:  
  b=b+1  
  print(b)  

2.9
### A cupcake costs A dollars and B cents. Determine, how many dollars and cents should one pay for N cupcakes. A program gets three numbers: A, B, N. It should print two numbers: total cost in dollars and cents.

  > a = int(input())  
b = int(input())  
n = int(input())  
price = a + (b/100)  
cost = price * n  
total=cost*100  
dollar=int(total//100)  
cents=int(total-(dollar*100))  
print(f'{dollar} {cents}')  

2.A.
### Days of week are numbered as: 0 — Sunday, 1 — Monday, 2 — Tuesday, ..., 6 — Saturday. An integer K in the range 1 to 365 is given. Find the number of day of week for K-th day of year provided that in this year January 1 was Thursday.   
  >a = int(input())  
if (a==0):  
  a=int(input())  
a=a+3  
if (a>=7):  
  a=a%7  
print(a)  

2.B.
### Given the integer N - the number of minutes that is passed since midnight - how many hours and minutes are displayed on the 24h digital clock?
  >n = int(input())  
hour = n//60  
min = n%60  
if (min<10):  
  minutes = f'0{min}'  
else:  
  minutes = f'{min}'  
print(f'{hour} {minutes}') 

2.C.
### ???????????????
  >

2.D.
### A school decided to replace the desks in three classrooms. Each desk sits two students. Given the number of students in each class, print the smallest possible number of desks that can be purchased.
  >counter = 0  
desk = 0  
while (counter != 3):  
  a = int(input())  
  desk = desk + (a//2)  
  if (a%2 != 0):  
    desk = desk+1   
  counter = counter + 1  
print(desk)  

3.1
### Given an integer, print "odd" if it's odd and print "even" otherwise. 
  >i = int(input())  
if(i%2 !=0):  
  print('odd')  
else:  
  print('even')  

3.2
### Given the two integers, print the least of them.
  >a = int(input())  
b = int(input())  
if (a<b):  
  print(a)  
else:  
  print(b)  

3.3 
### For the given integer X print 1 if it's positive, -1 if it's negative, or 0 if it's equal to zero.
  >i = int(input())  
if (i>1):  
  print(1)  
elif (i<0):  
  print(-1)  
else:  
  print(0)  

3.4
### Given an integer, print "YES" if it's a three-digit number and print "NO" otherwise.
  >a = int(input())  
if (a>99 and a<1000):  
  print('YES')  
else:  
  print('NO')  

3.5
### Given two non-zero integers, print "YES" if exactly one of them is positive and print "NO" otherwise.
  >a = int(input())  
b = int(input())  
if (a>0 and b>0):  
  print('NO')  
elif (a<0 and b<0):  
  print('NO')  
else:  
  print('YES')  

3.6
### Given a three-digit integer X consisting of three different digits, print "YES" if its three digits are going in an ascending order from left to right and print "NO" otherwise. 
>a = int(input())  
n1 = a//100  
a = a - (n1*100)  
n2 = a//10  
n3 = a - (n2*10)  
if (n2>n1 and n3>n2):  
  print('YES')  
else:  
  print('NO')  

3.7
### Given a four-digit integer, print "YES" if it's a palindrome and print "NO" otherwise. 
>a = int(input())  
while (a<=999 or a>=10000):  
  a = int(input())  
n1 = a//1000  
a = a-(n1*1000)  
n2 = a//100  
a = a-(n2*100)  
n3 = a//10  
n4 = a-(n3*10)  
if ((n1==n1) and (n2==n3)):  
  print('YES')  
else:  
  print('NO')  

3.8
### Given three integers, print the least of them.
>a = int(input())  
b = int(input())  
c = int(input())  
if (a<b and b<c):  
  print(a)  
elif(b<a and b<c):  
  print(b)  
else:  
  print(c)  

3.9
### Given a month - an integer from 1 to 12, print the number of days in it in the year 2017.
>thirtyOne = (1,3,5,7,8,10,12)  
a = int(input())  
if (a ==2):  
  print(28)  
elif(a in thirtyOne):  
  print(31)  
else:  
  print(30)  

3.A
### Given three integers. Determine how many of them are equal to each other. 
>a = int(input())  
b = int(input())  
c = int(input())  
if (a != b and b !=c and a !=c):  
  print(0)  
elif ((a ==b and b !=c) or (b==c and a!=c) or (a==c and b!=a)):  
  print(2)  
else:  
  print(3)  

3.B
### Given three integers, in which two are equal to each other and the third one is different. 
>a = int(input())    
b = int(input())    
c = int(input())  
if (a ==b and b !=c):  
  print(3)  
elif (b==c and a!=c):  
  print(1)  
else:  
  print(2)  

3.C.
### Given two different squares of the chessboard, determine whether a rook can go from the first square to the second one in a single move.
> x1 = int(input())  
y1 = int(input())  
x2 = int(input())  
y2 = int(input())  
if (x1==x2 or y1==y2):  
  print('YES')  
else:  
  print('NO')  

3.D
### Given a square of a chessboard. If it's a black square, print YES, otherwise print NO.
>a = int(input())  
b = int(input())  
if ((a%2 >0 and b%2 >0) or (a%2==0 and b%2==0)):  
  print('YES')  
else:  
  print('NO')  

3.E
### Given two squares of a chessboard. If they are painted in the same color, print YES, otherwise print NO.  
>x1 = int(input())  
y1 = int(input())  
x2 = int(input())  
y2 = int(input()) 
if ((x1%2 >0 and y1%2 >0) or (x1%2==0 and y1%2==0)):  
  if ((x2%2 >0 and y2%2 >0) or (x2%2==0 and y2%2==0)):  
    print('YES')  
  else:  
    print('NO')  
else:  
  if ((x2%2 >0 and y2%2 >0) or (x2%2==0 and y2%2==0)):  
    print('NO')  
  else:  
    print('YES')  