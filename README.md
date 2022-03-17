# march-17-Ass-1
Assigment-1
s=input()
l=list(s)
lr=0
ur = 0
d = 0
s = 0
for i in l:
    if (i.islower()):
     lr = lr+1 
    elif (i.isupper()):
        ur = ur+1 
    elif (i.isdigit()):
        d = d+1 
    else:
        s = s+1 
if(lr>0 and ur>0 and d >0 and s>0):
    print("The given passward is Valid")
else:
    print("Invalid passward")
