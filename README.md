"# sample"


n= int(input("enter a number"))
n1=int(input("enter a number"))
for i in range(n,n1+1):
  while i>=1:
    for j in range(2,i):
      if i%2==0:
        print("")
        break
    else:
      print(i,"")



  #
  a="Git and it's functions are located in the file"
  b={} 
  for i in range(a):
    if i in b.keys():
      b[i]=+1 
    else:
      b[i]=1
print(b)
