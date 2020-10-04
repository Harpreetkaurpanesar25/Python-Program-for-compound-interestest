# Python-Program-for-compound-interestest 
p=int(input("Enter the principle :"))  
t=int(input("Enter the time: "))    
r=int(input("Enter the rate: "))
a= p*(((1+ r/100)**t)) 

print("the amount is",a)
ci=a-p
print("the ci is",ci)

 
