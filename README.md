# Calculator
n1=int(input("Enter first number"))
n2=int(input("Enter second number"))
n=input("Enter type of operations: 1-add, 2-sub, 3-multiply, 4-divide")
print(f'Enter type of operations: ')
if (n==1):
    Print(f'n1+n2 is: {n1+n2})
elif(n==2):
    Print(f'n1-n2 is: {n1-n2})
elif(n==3):
    Print(f'n1*n2 is: {n1*n2})
elif(n==4): 
    Print(f'n1/n2 is: {n1/n2})
else:
    Print(f' Invalid Input')
    
    
    
# a=5 & b=6
a=5
b=6
a=a+b
b=a-b
a=a-b
print(f'a={a}')
print(f'b={b}')



# Prime Number from 1-100
a=int(input("Enter the Starting Number"))
b=int(input("Enter the Ending Number"))
for n in range(a,b+1):
    if n>1:
       for i in range(2,n):
           if (n%i)==0:
            break
       else:
           print(n)
           
           
# Fibonacci Number
n = int(input("Enter the number:  "))
n1, n2 = 0, 1
c = 0
if n <= 0:
   print("Please enter a positive integer")
elif n == 1:
   print("Fibonacci sequence upto",n,":")
   print(n1)
else:
   print("Fibonacci sequence:")
   while c < n:
       print(n1)
       n3 = n1 + n2
       n1 = n2
       n2 = n3
       c += 1




