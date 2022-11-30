### Lab 01
- list comprehension with double for and ifs

### Lab 02
- more list comprehensions, set comprehensions
- bit operations (task 7)
- any_string[::-1]
- .get(key, default_value)
- .values()
- .items() 
- .keys() 
- enumerate([])
- ''.join([])
- any_string.split() - default separator is any whitespace
- any_string.count(substring) - number of occurrences of a substring in the given string 


### Lab 03
- def func(**kwargs) gives kwargs dict 
- def func(*args) give args list 
- from types import GeneratorType - isinstance(values, GeneratorType)
- list(generator) - zmiana generatora na listę 
- attributes of function - ile_wywolana.call_counter = getattr(ile_wywolana, 'call_counter', 0)
- generator - def func(): ... yield result -  next values - gen = func(), next(gen)

### Lab 04
- func.__name__ (double underscore)
- from time import time, start = time(), end = time(), end - start (seconds)
- task 3 - derivative with epsilon 
- decorators 
- try: ... except TypeError: ....
- nonlocal name 
### Lab 05
- generator return ()
- map, filter 
- from functools import reduce
- magic methods (part07)
- self.__class__ (double underscore)
- @staticmethod, @classmethod

### Lab 06
- regexy, import re, re.match(pattern, str) - returns the first occurrence
- re.search(pattern, str) - returns a Match object if there is a match anywhere, result.groups()
- from collections import defaultdict, default_dict(lambda)


### Lab 07
- argparse 
- pickle.dump, pickle.load - saving classes to files
- ZoneInfo
- json.load, json.save