# Q.18-e-
def geometric_sum(n, a=1):
    if n == 0:
        return 0
    else:
        return a + geometric_sum(n-1, a*r)

n = int(input("Enter the number of terms: "))
r = float(input("Enter the common ratio: "))
print("The geometric sum of the first {} terms is:".format(n))
print(geometric_sum(n))
