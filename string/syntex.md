# 🈳 String

**Immutable** collection

<figure><img src="https://developers.google.com/static/edu/python/images/hello.png" alt=""><figcaption><p><a href="https://developers.google.com/edu/python/strings">List from Google Edu</a></p></figcaption></figure>

## Common Methods

| Method                                                                      | Use                                                                                                    | Description                                                                            |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| `join`                                                                      | `my_str.join([my_list])`                                                                               |                                                                                        |
| `find`                                                                      | `my_str.find(item)`                                                                                    | Return index of the first occurrence, `-1` otherwise                                   |
| `count`                                                                     | `my_str.count(item)`                                                                                   | Return number of occurrance                                                            |
| `split`                                                                     | `my_str.(delimiter)`                                                                                   | Return list of strings splits on delimiter                                             |
| `strip`                                                                     | `my_str.strip()`                                                                                       | Returns string with whitespace removed                                                 |
| `replace`                                                                   | `my_str.replace(old, new)`                                                                             |                                                                                        |
| <p><code>lower</code><br><code>upper</code></p>                             | <p><code>my_str.lower()</code>,<br><code>my_str.upper()</code></p>                                     |                                                                                        |
| <p><code>isalpha</code><br><code>isdigit</code><br><code>isspace</code></p> | <p><code>my_str.isalpha()</code><br><code>my_str.isdigit()</code><br><code>my_str.isspace()</code></p> |                                                                                        |
| <p><code>startswith</code><br><code>endswith</code></p>                     | <p><code>my_str.startswith('item')</code></p><p><code>my_str.endswith('item')</code></p>               |                                                                                        |
| <p><code>rjust</code><br><code>ljust</code><br><code>center</code></p>      | <p><code>my_str.rjust(w)</code><br><code>my_str.ljust(w)</code><br><code>my_str.center(w)</code></p>   | Return string _right-justified or left-justified_ or _centered_ in a field of size `w` |
