# Do Now 3.03

## In your console

### Type the following code:

```python
    import random
    # Inputs:  x (int), y (int)
    # Output: int
    # Purpose: 50% of time returns sum of x and y,
    #          otherwise returns product of x and y

    def mystery_function(x, y):
        random_number = random.randint(0,1)
        if random_number > 0:
            z = x + y
        else:
            z = x * y
        return z
    mystery_function(1, 2)
```

## In your notebook

### Answer the following questions:

1. What happens when your run this code? How do you know what the result was?
2. Keeping the function the same, adjust the code to print out the value that the function returns.
