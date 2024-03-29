from math import factorial
rows=int(input("enter the number of rows:"))
for n in range(rows):
    for space in range(1,rows-n):
        print(end='')
    for r in range(n+1):
        ncr=factorial(n)
        print(ncr,end='')
        print('')
    
