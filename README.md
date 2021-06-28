# python-try-except-handling
how to handle exception in python 
print("enter the number 1")
v1=input()
print("enter the second number")
v2=input()
try:
    print("sum of these number is",int(v1)+int(v2))
except Exception as p:
    print(p)
print("sorry you lost your connection")    
