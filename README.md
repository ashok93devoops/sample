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
