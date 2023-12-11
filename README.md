# armstrong-number
#check Armstrong number  using python
n=input()
a=len(n)
sum=0
for i in range(0,a):
  z=int(n[i])
  sum+=z**a
if sum==int(n)
  print("armstrong number:",sum)
else:
  print("not armstrong number")
