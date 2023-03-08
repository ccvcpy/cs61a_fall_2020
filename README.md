# cs61a_fall

# Disc 01: Environment Diagrams, Control [file_internet_link](https://inst.eecs.berkeley.edu/~cs61a/fa20/)

## 1.1
```python
    def wears_jacket(temp,raining):
        return temp<60 or raining
```

## 1.2
```python
    ''' def square(x):
            print("here!")
            return x * x

        def so_slow(num):
            x = num
            while x > 0:
            x = x + 1
            return x / 0
        print(square(so_slow(5)))

        #the result is infinite loop.(it's boring).
    '''
```
## 1.3
```python 
    def is_prime(n):
    """
        >>> is_prime(10)
        False
        >>> is_prime(7)
        True
    """
            for i in range(2,n//2):
            if n%i==0:
                return False
            return True
```
## 2.1
![2.1](https://github.com/ccvcpy/cs61a_fall/blob/main/image/2.1.png)
## 2.2
![](image\2.2.png)
## 2.3
![](image\2.3.png)
## 2.4 
```python
    def f(x):
        return x
    def g(x, y):
        if x(y):
            return not y
        return y
    x = 3
    x = g(f, x)
    f = g(f, 0)Global frame
```
![](image\2.4.jpg)
