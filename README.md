# neon number
a=int(input("enter a  no"))
b=a**2
print(b)
temp=b
rev=0
while(temp>0):
    rem=temp%10
    rev=rev+rem
    temp=temp//10
if(rev==a):
    print("it is nano number")
else:
    Print("it is not neon number") 
