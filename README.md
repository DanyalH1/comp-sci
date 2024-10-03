# comp-sci
U2L1: A = [2, 8, 6, 3, 9, 1, 7]
B = [0] * len(A)

shift = 2

for i in range(len(A)):
    B[i] = A[(i + shift) % len(A)]

print(B)

U2L2: 
inches = 10 ** 12  # one trillion
(foot, inches) = divmod(inches, 12)
(yards, foot_) = divmod(foot, 3)
(miles, yards_) = divmod(yards, 1760)
(MoonDistance, miles_) = divmod(miles, 238855) 

print("One trillion inches is the same as")
print(MoonDistance, "Distances between earth and the moon;", miles_, "miles;", yards_,
      "yards;", foot_, "feet; and", inches, "inches")
