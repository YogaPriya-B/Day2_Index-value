# Day2_Index-value


Day 2:

arr=list(map(int,input().strip().split()))

product=1

l=[]

for i in arr:

    product=product*i

print(product)

for j in arr:

    c=product//j 

    l.append(c)

print(l)
