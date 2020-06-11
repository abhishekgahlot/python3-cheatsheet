# Python3 for competitive programming or coding interviews


### Set of lowercase, uppercase and lowercase + uppercase
```
from string import ascii_lowercase, ascii_uppercase, ascii_letters
```

### Permutation and Combination
```
from itertools import permutations, combinations
```

### Counter
```
from collections import Counter

eg = [1,2,3,4,5]
print(Counter(eg)) # Counter({1: 1, 2: 1, 3: 1, 4: 1, 5: 1})
```

### LRU Cache Decorator
#### Important for caching values of function fast, Rather than using dict yourself.
```
  from functools import lru_cache

  @lru_cache(maxsize=None)
  def fib(n):
      if n < 2:
          return n
      return fib(n-1) + fib(n-2)

  print([fib(n) for n in range(40)]) # Won't be fast without this decorator

  print(fib.cache_info())

```

### Check if char is alphanumeric
```
  '2'.isalnum()
```

### Sets

#### Union

```
  set(a) | set(b) # a,b are iterables

  a.union(b) # Given a and b are already set
```

#### Intersection ( Comman Items )
```
  set(a) & set(b)

  a.intersection(b)
```

#### Subtract Sets

```
  # for a set a,b 
  a - b # Prints items not in y that are in x
  b - a # Prints items not in x but are in y
```


### Tranpose of Matrix
```
  zip(*matrix)
```
