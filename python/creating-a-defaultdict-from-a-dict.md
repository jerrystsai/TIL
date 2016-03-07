# Creating a defaultdict from a dict

Recalling that for a `defaultdict`, you must specify the default datatype for the value.
Just add the `dict` as the second argument in the `defaultdict` class. For example,
if the default value is an integer:

```
the_defaultdict = defaultdict(int, the_dict)
```
