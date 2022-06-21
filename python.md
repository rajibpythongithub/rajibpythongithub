# 1. Write a program to reverse an integer.
```
num = int(input("Enter a number : "))
rev = 0
while(num > 0):
    rem = num % 10  #modulo operation
    rev = (rev * 10) + rem
    num = num // 10 #// - floor division
print("After reverse : ", rev)
```
```
Enter a number : 1234
After reverse : 4321
```    
      
# 2. Write a  program to a number check Armstrong number or not.
```
num = int(input("Enter a number : "))
sum = 0
temp = num
while(temp>0):
    digit = temp % 10
    sum = sum + (digit ** 3)
    temp = temp // 10
if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")
```
```
Enter a number : 153
153 is an Armstrong number
```
# 3. Write a program to check a number is a Prime number or not.
```
num = 5
for i in range(2, num):
    if num%i==0:
        print(num,"is not a prime number")
        break
else:
    print(num,"is a prime number")
```
```
5 is a prime number
```
# 4. Write a program to print prime number from 1 to 10.
```
lower = 1
upper = 10
for num in range(lower, upper+1):
    if num>1:
        for i in range(2,num):
            if(num%i)==0:
                break
        else:
            print(num)
```
```
2
3
5
7
```
# 5. Write a program to print Fibonacci series program in using iterative methods.
```
n = 5
first = 0
second = 1
for i in range(0,n):
    if i<=1:
        result = i                          
    else:
        result = first + second;           
        first = second;                    
        second = result;                    
    print(result)
```
```
0
1
1
2
3
```
# 6. Write a program to print fibinacci series using recursive method.
```
def fibonacci(num):
    if num==0:
        return 0
    elif num==1:
        return 1
    else:
        return fibonacci(num-2) + fibonacci(num-1)

for x in range(5):
    print(fibonacci(x))
```
```
n = int(input("please give a number for fibonacci series : "))
def fibonacci(num):
    if num == 0:
        return 0
    elif num == 1:
        return 1
    else:
        return fibonacci(num-1)+fibonacci(num-2)
print("fibonacci series are : ")
for i in range(0,n):
    print(fibonacci(i))
```
```
0
1
1
2
3
```
