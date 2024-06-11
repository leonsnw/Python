## Mutable Objects

1. What would be the output of the following program? explain

```
x = [1, 2 ,3]
y = x
print(x)
print(y)
x[0] = 0
print(x)
print(y)
```

### Solution

```
[1, 2, 3]
[1, 2, 3]
[0, 2, 3]
[0, 2, 3]
```
