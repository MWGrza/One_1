# One_1
New Begining
## The program is calculating yearly payment on credit car with minimum payments

a =  round(float(raw_input( "Enter the outstanding balace on your credit card: ") ), 2)
i = round(float(raw_input( "Enter the anual credit card intrest rate as a decimal: ") ), 5)
j = round(float(raw_input("Enter the minimum monthly payment rate as a decimal: ")),5)
x = 1
mysum = 0

while x< 13:
    print " Month: ", x 
    x = x +1
    g = round (  (a *( i/12) ), 2)
    f = round ( (j * a) ,2)
    b = round (f -  g, 2) 
    a = round ( a - b , 2)
    print "Minimum monthly payment: $" ,  f
    print "Principle paid:  $" ,b
    print "Remaining balance: $ " , a
    mysum += f
print "RESULT"    
print "Total sum paid: $", mysum
print "Remaining balance: $" ,a 
