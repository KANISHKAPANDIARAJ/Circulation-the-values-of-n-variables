# Circulation-the-values-of-n-variables
a = 1
b = 2
c = 3
d = 4
print("Before circulate")
print("a=",a,"b=",b,"c=",c,"d=",d)
a=a+c
b=a-c
d=a-b
c=d-b
print("After circulate")
print("a=",a,"b=",b,"c=",c,"d=",d)
