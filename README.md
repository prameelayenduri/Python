num=int(input("enter a number"))
for i in range(1,num+1):
    print(" "*(num+i),end="")
    for j in range(1,i+1):
        print("*",end="")
    print()



num=int(input("enter a number"))
for i in range(1,num+1):
    print(" "*(num+i),end="")
    for j in range(1,i+2):
        print("2",end="")
    print()


num=int(input("enter a number"))
for i in range(1,num+1):
    print(" "*(num-i),end="")
    for j in range(1,i+3):
        print("@",end="")
    print()
