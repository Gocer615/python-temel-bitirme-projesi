# python-temel-bitirme-projesi
1. proje

x=[[1,'a',['cat'],2],[[[3]],'dog'],4,5]

liste = []

def f(a):
    for i in a:
        if type(i)==list:
            f(i)
        else:
            liste.append(i)

f(x)            

print(liste) 

2. proje


a.reverse()
for i in a:
    i.reverse()
print(a)
