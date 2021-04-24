# prime-numbers-in-python
num =25
flag = False
if num > 1:
    for i in range(2, num):
        if (num % i) == 0:
           
            flag = True
           
            break

if flag:
    print(num, 'is not a prime')
else:
    print(num, "is a prime number")
