# comp-sci
U2L1: A = [2, 8, 6, 3, 9, 1, 7]
B = [0] * len(A)

shift = 2

for i in range(len(A)):
    B[i] = A[(i + shift) % len(A)]

print(B)
