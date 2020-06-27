# A crispy way to find the factorial of a number through PYTHON.

def factorial(num):
    return num < 2 or num * factorial(num-1)
