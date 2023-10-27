#Program 1. WAP to find the roots of a quadratic equation.

#Code =

a,b,c = eval(input("enter value "))

d = b ** 2 - 4 * a * c

r1 = (-b + (d) ** 0.5) / 2 * a

r2 = (-b - (d) ** 0.5) / 2 * a

if d >=0:

 print("roots are real " ,r1 ,r2)

else:

 print("roots are not real")

#output=

enter value 3,6,9

roots are not real

enter value 3,9,4

roots are real -4.883156030192957 -22.116843969807043
