# Python-programs

# area of rectangle 
a=int(input("Enter the length"))
b=int(input("Enter the breadth"))
area=a*b
print("area",area)

# area of circle
r=int(input("Enter the radius: "))
area=3.14*r*r
print("area",area)

# perimeter of rectangle 
l=int(input("Enter the length: "))
b=int(input("Enter the breadth"))
perimeter=2*(l+b)
print("Perimeter :", perimeter)


# Simple Interest

p = float(input("Enter Principal (P): "))
r = float(input("Enter Rate of Interest (R): "))
t = float(input("Enter Time in years (T): "))

si = (p * r * t) / 100

print("Simple Interest =", si)


# Celsius to Fahrenheit Conversion

c = float(input("Enter temperature in Celsius: "))

f = (9/5) * c + 32

print("Temperature in Fahrenheit =", f)
