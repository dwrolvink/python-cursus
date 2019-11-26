- data types: string, int, float, objects
- objects: class objects, system objects (lists, tuples, dictionaries)

| system object | properties |
| :------------ | :--------- |
| List          | Lijst van vars, mutable |
| Tuple         | Lijst van vars, immutable |
| dictionary    | "hashtable", lijst van named vars|

#### list 
```python
l = []     # empty list
l = list() # empty list
l = ['a', 1]

# muteren list
l.append('b')
l += 2
l # output: ['a', 1, 'b', 2]

# select output
l[2]   # output: 'b'
l[0] = 'z'
l[0:2] # output: ['z', 1]
```

Zie ook https://realpython.com/python-strings/


#### tuple 
````python
# tuple
t = tuple() # empty tuple
t = ()      # empty tuple
t = (1, 2)

# muteren tuple mag niet!
t[0] = 'z' # output: (...) TypeError: 'tuple' object does not support item assignment

# Type casting (convert tuple to list)
l = list(t)
l[0] = 'z'
l # output: ['z', 2]

```

#### Dictionary
Zie [Dictionaries](https://python101.pythonlibrary.org/chapter3_lists_dicts.html#dictionaries)

## Zie ook:
- `type(var)`


