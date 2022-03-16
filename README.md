PROGRAMME:
s=input()
l=list(s)
print(l)
res=[]
for i in l:
    if i not in res:
        res.append(i)
for i in res:
    print(i,end='')
OUTPUT:

1231233553
['1', '2', '3', '1', '2', '3', '3', '5', '5', '3']
1235
