# demo 1
import math
a=input("ENTER THE FIRST COORDINATE")
n1=a.split(",")
b=input("ENTER THE SECOND COORDINATE")
n2=b.split(",")
d=math.sqrt(((int(n1[0])-int(n2[0]))**2)+((int(n1[1])-int(n2[1]))**2))
print("DISTANCE IS : ",d)
