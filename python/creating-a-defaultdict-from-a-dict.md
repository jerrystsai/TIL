# Creating a defaultdict from a dict


```clojure
> (merge-with + {:a 1 :b 3} {:b 2 :c 3} {:c 1 :d 4})
{:a 1, :b 5, :c 4, :d 4}
```

Recalling that for a `defaultdict`, you must specify the default datatype for the value.
Just add the `dict` as the second argument in the `defaultdict` class. For example,
if the default value is an integer:

```
the_defaultdict = defaultdict(int, the_dict)
```
