# Problem #5 [**Medium**]

```cons(a, b)``` constructs a **pair**, and ```car(pair)``` and ```cdr(pair)``` returns the **first** and **last element** of that **pair**. 

## Example

### Input
```python
car(cons(3, 4))
``` 
### Output
```python
3
```

### Input
```python
cdr(cons(3, 4))
```
### Output
```python
4
```

Given this implementation of cons:

```python
def cons(a, b):
    def pair(f):
        return f(a, b)
    return pair
```


Implement car and cdr.