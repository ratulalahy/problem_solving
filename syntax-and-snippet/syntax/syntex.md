# 🚈 Array

_**ordered**_ collection of zero or more _**references**_ to data objects.

## Common Methods

| Method    | Example                  | Description                                      |
| --------- | ------------------------ | ------------------------------------------------ |
| `append`  | `a_list.append(item)`    | Append new item to the end                       |
| `insert`  | `a_list.insert(i, item)` | Insert an item at the $i^th$ position.           |
| `pop`     | `a_list.pop()`           | Removes+Returns the last item                    |
| `pop`     | `a_list.pop(i)`          | Removes+Returns $i^th$ item                      |
| `sort`    | `a_list.sort()`          | Inplace sort the list                            |
| `reverse` | `a_list.reverse()`       | Inplace reverse order the list                   |
| `del`     | `del a_list[i]`          | Delete $i^th$ item                               |
| `index`   | `a_list.index(item)`     | Return the index of first occurrence of the item |
| `count`   | `a_list.count(item)`     | Returns number of occurrence of the item         |
| `remove`  | `a_list.remove(item)`    | Remove the the first occurrence of the item.     |

## Sorting

|    Attribute    |      list.sort()     |                                               sorted(list)                                              |
| :-------------: | :------------------: | :-----------------------------------------------------------------------------------------------------: |
|     Returns     |         None         |                                             New sorted list                                             |
|     Inplace?    |          Yes         |                                      <p>No.<br>Returns new list</p>                                     |
|    Efficiency   |        Faster        |                              <p>Slower.<br>'Coz needs to copy new list.</p>                             |
| Other iterables | Only works with list | <p>Works on any iterables.<br>Strings, tuples, dictionaries (you'll get the keys), generators, etc.</p> |

> ref : [https://stackoverflow.com/a/22442440/565055](https://stackoverflow.com/a/22442440/565055)

{% embed url="https://www.w3schools.com/python/ref_list_sort.asp" %}

## Shorthand `if` `else`

```python
x = 10 if a > b else 11
```
