# basic-Calculator

a=float(input("inter your 1st number:"))
b=float(input("inter your 2nd number: "))
c=str(input("what do you want to do\nmultiply\ndivide\nadd\nsubstract\nsqaure root:"))

if c=="multiply":
    print("your result is:",a*b)
elif c=="divide":
    print("your result is:",a/b)
elif c=="add":
    print("your result is:",a+b)
elif c=="substract":
    print("your result is:",a-b)
elif c=="sqaure root":
    print("your result is:",a**b)
else:
    print("incorrect operation.please try form listed operation")
