import math

S = (12.48 * (5.76 ** (1/3)) * math.sin(math.radians(4))) / ((1842 ** (4/3)) * (673.8 ** (1/3)) * math.cos(math.radians(8)))
t = math.log10((3 ** (1/3)) ** (1/3)) - 1/4
st = S * t

if st < 0:
    n = (S - 2 * t) / (2 * S*2 + 5 * t*2)
else:
    n = math.sqrt(3 * t)

print(n)
