# ASSIGNMENT-2
n=int(input('enter numb:'))
for i in range(1,n+1): 
    for j in  range(1,i+1):
        print(j,end=' ')
    print('\n')
for i in range(0,n):
    for j in  range(1,n-i):
        print(j,end=' ')
    print('\n')
