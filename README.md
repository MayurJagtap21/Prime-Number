# Prime-Number
Code for search either given number is prime number or not

n = int(input())
checker = 0
for divisor in range (2, n//2 + 1):
    if(n % divisor == 0):
        checker = 1
        print("n is not a Prime Number")
        break

if (n != 1 and checker == 0):
    print("n is Prime Number")
elif (n == 1):
    print("n is not a prime Number")
