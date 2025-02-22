#3sum

num=[2,7,11,15]
tar=27
f=False
for i in range(len(num)-1):
    for j in range(i+1,len(num)):
        for k in range(j+1,len(num)):
            if num[i]+num[j]+num[k]==tar:
                print ([i,j,k])
                f=True
if not f:
    print("none")
