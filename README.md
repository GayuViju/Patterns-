n=int(input("Enter the number"))
c=0
if(n<=26):
   a=65
   c=65
   for i in range(n):  
    j=0
    while((j+65)<=a):
         print(chr(j+65),end=" ")
         j+=1
    a=a+1
    print("\b")

         
         
