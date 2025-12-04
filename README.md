# python_note
list mutating methods: 
1. append(x): add x at the end of the list.  
2. extend(iterable): extend by each element.  
3. insert(i, x): insert x at index i.  
4. remove(x): remove first x occurence.    
5. pop([i]): remove and return element, pop() removes last element.
6. clear(): remove all elements.
7. sort(): in-place sort.
8. reverse(): in-place reverse.

dict:
creating dict:
d1 = {"a": 1, "b": 2}
d2 = dict([("a", 1), ("b", 2)])

keys = ["a", "b"]; vals = [1, 2]
d3 = dict(zip(keys, vals))
d4 = dict(a=1, b=2)

d = {"x": 10, "y": 20}
d["z"] = 30      # insert
d["x"] = 15  # update existing

dict methods:
1. d.keys(), d.values(), d.items() --> views
2. d.get(k, default=None) --> safe lookup
3. d.setdefault(k, default=None) --> return value if exists, else set key to default and return it
4. d.update(other) --> merge mapping or pairs into d
5. d.clear() --> remove all items
6. d.pop(k, default) --> remove and return value or default
7. d.popitem() --> remove and return last inserted (key, value), raises KeyError if empty
8. d.copy() --> shallow copy
9. d.items() supports for k, v in d.items()

set methods:
--> add(x): Adds one element, x.  
--> update([x, y, z]): Adds multiple elements; x, y, z.  
--> remove(x): Removes the given element, x. Raises error if missing.  
--> discard(x): Removes the given element, x. Safe remove.  
--> pop(): Removes one random element.  
--> clear(): Clears the set.

set operations:
1. Union (combine elements): a | b or a.union(b)
2. Intersection (common elements): a & b or a.intersection(b)
3. Difference (elements in a, not in b): a - b or a.difference(b)
4. Symmetric Difference (elements not shared): a ^ b or a.symmetric_difference(b)  






