def add(x,y):
    return x+y
def sub(x,y):
    return x-y
def mul(x,y):
    return x*y
def div(x,y):
    return x/y
a=float(input("Enter first number: "))
b=float(input("Enter second number: "))
op=input("Enter operator (+,-,*,/): ")
if op=='+':
    print(add(a,b))
elif op=='-':
    print(sub(a,b))
elif op=='*':
    print(mul(a,b))
elif op=='/':
    print(div(a,b))
Output
Enter first number: 10
Enter second number: 5
Enter operator (+,-,*,/): *
50.0
