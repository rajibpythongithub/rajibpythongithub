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
