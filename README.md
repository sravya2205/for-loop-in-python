#Write a Python program that uses a for loop to print the numbers from 1 to 10.
for i in range(1,11):
    print(i)

    #Create a program that uses a for loop to calculate the sum of the first 100 natural numbers.
sum=0
for i in range(0,101):
    sum=sum+i
print(sum)

#Create a program that uses a for loop to calculate the sum of the first 100 natural numbers.
sum=0
for i in range(0,101):
    sum=sum+i
print(sum)

#Implement a function that uses a for loop to find the factorial of a given number.
num=int(input())
fact=1
for i in range(1,num):
    fact=fact*i
print(fact)

#Write a Python script that uses a for loop to iterate over a list and print each element.
list=[1,"sravya","python",2.25]
for i in list:
    print(i,end=' ')

    #Develop a program that uses a for loop to print the square of each number in a given list.
list=[1,8,10,7,20]
for i in list:
    result=i*i
    print(result)

    #Create a function that uses a for loop to count the number of vowels in a given string.
def count():
    vowels='aeiou'
    str="sravini"
    for char in vowels:
        if char in str:
            print(str.count(char))
count()


#Write a Python program that uses a for loop to iterate over the characters of a string and print their ASCII values.
str="python"
for char in str:
    print(ord(char))

    #Implement a function that uses a for loop to check if a given list contains any negative numbers
list=[1,2,3,4,-3,-2,24,-45,90]
for i in list:
    if i<0:
        print(i)

        #Develop a program that uses a for loop to find the maximum value in a list of numbers.
list=[1,2,40,100,34,80]
for i in list:
    print(max(list))

    #Create a Python script that uses a for loop to print the multiplication table for a given number.
num=int(input())
for i in range(1,11):
    print(f"{num}*{i}={num*i}")
