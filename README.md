# ASsignment-5-10-05-2022
Assignment 5
n=int(input())
d={}
for i in range (n):
    x=input().split()
    d[x[0]]=x[1]
while True:
    try:
        name=input()
        if name in d:
            print(name,'=',d[name])
        else:
            print(" Not Found")
    except:
        break
