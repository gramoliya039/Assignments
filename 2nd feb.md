Q1 answer: 
Use a for loop when you know the number of iterations beforehand or when you want to iterate over a sequence (like a list or an array) a specific number of times.
for i in range(2, 12, 2):
    print(i)

Use a while loop when you want to repeat a block of code as long as a certain condition is true. 
This is useful when the exact number of iterations is uncertain or when the loop needs to continue until a specific condition is met.
#include <iostream>
using namespace std;


    int sum = 0;
    int num = 1;
while sum<100:
  sum+= 1
print(sum)


Q2 Answer :
Write a python program to print the sum and product of the first 10 natural numbers using for loop
sum= 0
product = 1

for i in range(1,11):
    sum = sum + i
    product = product * i
print("sum of 10 natural num is :", sum)
print("product of 10 natural number is", product)




Write a python program to print the sum and product of the first 10 natural numbers using While loop
sum= 0
product = 1
num = 1

while num<= 10:
    sum = sum + num
    product = product * num
    num += 1
print("sum of 10 natural num is :", sum)
print("product of 10 natural number is", product)

Q3 Answer:
