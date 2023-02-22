# 🍡 Set

**Unordered, immutable** Collection

## Operators

| Operator | Use                      | Explanation                                  |
| :------: | ------------------------ | -------------------------------------------- |
|   `in`   | `x`` `_`in`_` ``my_set`  | Check if `x` is member of `my_set`           |
|   `len`  | `len(my_set)`            | Returns cardinality or len of `my_set`       |
|   `\|`   | `set_1 \| set_2`         | Returns new set of Union                     |
|    `&`   | `set_1 & set_2`          | Returns new set of Intersection              |
|    `-`   | `set_1 - set_2`          | Returns new set of Difference                |
|   `<=`   | `set_1 <= set_2`         | Returns if `set_1` is subset (⊆) of `set_2`  |

## Methods

|     Method     | Equiv | Use                         |                  Explanation                 |
| :------------: | ----- | --------------------------- | :------------------------------------------: |
|     `union`    | `\|`  | `set_1.union(set_2)`        |           Returns new set of Union           |
| `intersection` | `&`   | `set_1.intersection(set_2)` |       Returns new set of Intersection        |
|  `difference`  | `-`   | `set_1.difference(set_2)`   |        Returns new set of Difference         |
|   `issubset`   | `<=`  | `set_1.issubset(set_2)`     | Returns if `set_1` is subset (⊆) of `set_2`  |
|      `add`     |       | `my_set.add(item)`          |            Add `item` to `my_set`            |
|    `remove`    |       | `my_set.remove(item)`       |          Remove `item` from `my_set`         |
|      `pop`     |       | `my_set.pop()`              |          Remove _**arbitrary**_ item         |
|     `clear`    |       | `my_set.clear()`            |        Removes all item from `my_set`        |
