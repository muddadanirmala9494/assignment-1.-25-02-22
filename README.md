# assignment-1.-25-02-22




#write a python program to move positive numbers to find and negative numbers to last.
l=[]
p=[]
n=[]
num=int(input('enter the number'))
for i in range(1,num+1):
    x=int(input())
    l.append(x)
for j in range(num):
    if(l[j]>=0):
        p.append(l[j])
    else:
        n.append(l[j])
print('positive list:',p)
print('negative list:',n)
