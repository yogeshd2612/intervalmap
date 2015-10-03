This class maps intervals to values.
Example:
```
>>> i = intervalmap()
>>> i['08:00' : '12:00'] = 'Mister A'
>>> i['12:00' : '16:00'] = 'Mister B'
>>> print i['11:37'] 
Mister A
```

Inspired by this [recipe](http://code.activestate.com/recipes/457411/).