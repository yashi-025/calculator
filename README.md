# calculator  code in python
print("enter number:")
a,b=map(int,input().split())
print("enter operation to be performed:")
operator=input()
print("output:")
if operator=='+':
    print(a+b)
elif operator=='-':
    print(a-b)
elif operator=='*':
    print(a*b)
elif operator=='/':
    print(a/b)    
