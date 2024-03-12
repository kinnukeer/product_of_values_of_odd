# product_of_values_of_odd
#product of values of odd
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
r=1
for i in d:
  if i%2!=0:
    r=r*d[i]
print(r)


