# Candy-Distribution
# cook your dish here
for i in range (int(input())):
    n,m = map(int,input().split())
    a=n%m
    if(a==0 and a%2==0):
        print("yes")
    else:
        print("no")
