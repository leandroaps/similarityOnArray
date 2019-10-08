# similarityOnArray
This snippet can be used to return an array of elements that appear in two arrays.

```
const similarityOnArray = (arr, values) => arr.filter(v => values.includes(v));
```

**Usage:**
```
similarityOnArray([1, 2, 3], [1, 2, 4]); // [1, 2]
```
