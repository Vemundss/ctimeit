# ctimeit
A timeit decorator for python functions

### Installation:
`pip install ctimeit`

### Example Usage:
Replaces the following code:
```python
from timeit import default_timer as timer

def my_example_func(*args,**kwargs):
  """do some calculations and store in result"""
  return result

start = timer()
output = my_func(*args, **kwargs)
end = timer()

useful_info_str = "It took this many seconds"
print(useful_info_str, end-start)
```
With:
```python
from ctimeit import ctimeit

@ctimeit
def my_example_func(*args,**kwargs):
  """do some calculations and store in result"""
  return result
```


### Links to Project
Github link: 
https://github.com/Vemundss/ctimeit

PyPi link:
https://pypi.org/project/ctimeit/
