# geometric-mean.py

c = 0
p = 1.0
count = int(input("Enter the number of values: "))
while(c<count):
    x = float(input("Enter a real number: "))
    c = c+1
    p = p * x
gm = pow(p,1.0/count)
print("The geometric mean is: ",gm)



output:
Enter the number of values: 3
Enter a real number: 5
Enter a real number: 67
Enter a real number: 6
The geometric mean is:  12.620174282199963


