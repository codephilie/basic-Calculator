# Basic calculator

a=float(input("enter your 1st number:"))
b=float(input("enter your 2nd number: "))
c=str(input("what do you want to do\nmultiply\ndivide\nadd\nsubstract\npower:"))


if c=="multiply":
    print("your result is:",a*b)
elif c=="divide":
    if b!=0:
      print("your result is:",a/b)
    else:
        print("error:can not divided by zero")
elif c=="add":
    print("your result is:",a+b)
elif c=="subtract":
    print("your result is:",a-b)
elif c=="power":
    print("your result is:",a**b)
else:
    print("incorrect operation. please choose form listed operations")

