# 🏳 Dictionary

## Operators

| Operator | Use              | Explanation                                                                                  |
| :------: | ---------------- | -------------------------------------------------------------------------------------------- |
|   `[]`   | `my_dict[key]`   | Returns `value` of `key` if found. Otherwise <mark style="color:orange;">`error`</mark>.     |
|   `in`   | `key in my_dict` | <p>Returns <code>True</code> if <code>key</code> exists.<br>Otherwise <code>False</code></p> |
|   `del`  | `del my_dict[i]` | Removes `i` th item.                                                                         |

## Methods

|  Method  | Use                     | Explanation                                                                                        |
| :------: | ----------------------- | -------------------------------------------------------------------------------------------------- |
|  `keys`  | `my_dict.keys()`        | Returns the keys                                                                                   |
| `values` | `my_dict.values()`      | Returns values of the dictionary                                                                   |
|  `items` | `my_dict.items()`       | Returns all `key:value` pairs of the dict                                                          |
|   `get`  | `my_dict.get(key)`      | <p>Returns <code>value</code> of <code>key</code> if found. </p><p>Otherwise <code>None</code></p> |
|   `get`  | `my_dict.get(key, alt)` | <p>Returns <code>value</code> of the <code>key</code> if found.<br>Otherwise <code>alt</code></p>  |
