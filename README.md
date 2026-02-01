# 63.-Geometric-mean-of-n-numbers
count = int(input("Enter the number of values: "))
c = 0
product = 1.0

while c < count:
    x = float(input("Enter a real number: "))
    product *= x
    c += 1

gm = product ** (1.0 / count)
print("The geometric mean is:", gm)
