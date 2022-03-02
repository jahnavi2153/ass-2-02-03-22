# ass-2-02-03-22
#Program to multiply two matrices
a=[[1,2,3],
   [4,5,6],
   [7,8,9]]
   
b=[[9,8,7],
   [2,3,5],
   [6,2,8]]
   
c=[[0,0,0],
   [0,0,0],
   [0,0,0]]
for i in range(len(a)):
    for j in range(len(a[0])):
        c[i][j]=a[i][j]*b[i][j]
print(c)

output:
[[9,16,21], [8,15,30], [42,16,72]]
