[![HitCount](http://hits.dwyl.com/swapnanildutta/Python-programs.svg)](http://hits.dwyl.com/swapnanildutta/Python-programs)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 
# Python-programs
#Fibonacci sequence 
def fib(n):
    if n<=1:
        return n
    else:
        f=fib(n-1)+fib(n-2)
        return f
n=int(input("Enter a value to find fibonacci seq:"))
print(fib(n))
