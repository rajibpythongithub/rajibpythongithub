# 1. program to reverse an integer?
```
num = int(input("Enter a number : "))
rev = 0
while(num > 0):
    rem = num % 10  #modulo operation
    rev = (rev * 10) + rem
    num = num // 10 #// - floor division
print("After reverse : ", rev)

o/p : Enter a number : 1234
      After reverse : 4321
```    
      
# 2. check Armstrong number or not?
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
   
o/p : Enter a number : 153
      153 is an Armstrong number
```
