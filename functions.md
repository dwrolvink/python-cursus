# Functions
https://python101.pythonlibrary.org/chapter10_functions.html

### Built-in
```python
print("hoi")
a = {"one":1, "two":2}
type(a) # output: <class 'dict'>
```

### Custom functions
```python 
def a_function():
    print("You just created a function!")
    
def add(a, b):
    return (a + b)
```

# Classes en Methods
```python
class Bal():
    def __init__(self, color):
        self.color = color
        self.mood = "Happy"
        
    def trap(self):
        print("Auw!")
        self.mood = "sad"

b = Bal('blauw')
b.color   # output: 'blauw'
b.mood    # output: 'Happy'
b.trap()  # output: Auw!
b.mood    # output: 'sad'
```

# Parameter passing: pass by value / pass by reference
```python
a = [0,1]
b = a
b.append(2)
a
```
