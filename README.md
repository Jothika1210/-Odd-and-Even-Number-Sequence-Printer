# -Odd-and-Even-Number-Sequence-Printer

n=int(input("enter the limit"))
if n%2==0:
    for i in range(n-1,0,-2):
        print(i)
    else:
        for i in range (n,0,-2):
            print(i)

OUTPUT

enter the limit 10
9
7
5
3
1
10
8
6
4
2

