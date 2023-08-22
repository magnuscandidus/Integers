# Integers
# cook your dish here
N=int(input()) 
c=0
for i in range(1, N+1) :
    for j in range(1, N+1) :
        if(i+j==N) :
            c=c+1
print(c)
