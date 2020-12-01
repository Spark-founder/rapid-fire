x=int(input("Enter the Value of x"))
ouc=int(input("Enter Occurence"))
def fact(n):
    return 1 if (n == 0 or n == 1) else n * fact(n - 1)

def main(x,ouc):
    sum=0
    for i in (0,ouc):
        sum+=i*x/fact(i)
        print(sum)
    print(sum)
if __name__=='__main__':
    main(x,ouc)
