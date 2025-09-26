# Basic calculator

a=float(input("enter your 1st number:"))
b=float(input("enter your 2nd number: "))
c=str(input("what do you want to do\n1:multiply\n2:divide\n3:add\n4:substract\n5:power:\nenter your operation:"))


if c=="1":
    print("your result is:",a*b)
elif c=="2":
    if b!=0:
      print("your result is:",a/b)
    else:
        print("error:can not divided by zero")
elif c=="3":
    print("your result is:",a+b)
elif c=="4":
    print("your result is:",a-b)
elif c=="5":
    print("your result is:",a**b)
else:
    print("incorrect operation. please choose form listed operations")



