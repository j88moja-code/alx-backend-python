## 0x00-python_variable_annotations

`mandatory_tasks`

* [0-add.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/0-add.py) - a type-annotated function `add` that takes a float `a` and a float `b` as arguments and returns their sum as a float.
* [1-concat.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/1-concat.py) - a type-annotated function `concat` that takes a string `str1` and a string `str2` as arguments and returns a concatenated string
* [2-floor.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/2-floor.py) - a type-annotated function `floor` which takes a float `n` as argument and returns the floor of the float.
* [3-to_str.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/3-to_str.py) - a type-annotated function `to_str` that takes a float `n` as argument and returns the string representation of the float.
* [4-define_variables.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/4-define_variables.py) - Define and annotate the following variables with the specified values:

	* `a`, an integer with a value of 1
	* `pi`, a float with a value of 3.14
	* `i_understand_annotations`, a boolean with a value of True
	* `school`, a string with a value of “Holberton”
* [5-sum_list.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/5-sum_list.py) - a type-annotated function `sum_list` which takes a list `input_list` of floats as argument and returns their sum as a float.
* [6-sum_mixed_list.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/6-sum_mixed_list.py) - a type-annotated function `sum_mixed_list` which takes a list `mxd_lst` of integers and floats and returns their sum as a float.
* [7-to_kv.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/7-to_kv.py) - a type-annotated function `to_kv` that takes a string `k` and an int OR float `v` as arguments and returns a tuple. The first element of the tuple is the string `k`. The second element is the square of the int/float `v` and should be annotated as a float.
* [8-make_multiplier.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/8-make_multiplier.py) - a type-annotated function `make_multiplier` that takes a float `multiplier` as argument and returns a function that multiplies a float by `multiplier`.
* [9-element_length.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/9-element_length.py) - Annotate the below function’s parameters and return values with the appropriate types 
```
def element_length(lst):
    return [(i, len(i)) for i in lst]
```

`advanced_tasks`

* [100-safe_first_element.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/100-safe_first_element.py) - Augment the following code with the correct duck-typed annotations:
```
# The types of the elements of the input are not know
def safe_first_element(lst):
    if lst:
        return lst[0]
    else:
        return None
```
* [101-safely_get_value.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/101-safely_get_value.py) - Given the parameters and the return values, add type annotations to the function
```
def safely_get_value(dct, key, default = None):
    if key in dct:
        return dct[key]
    else:
        return default
```
* [102-type_checking.py](https://github.com/j88moja-code/alx-backend-python/blob/main/0x00-python_variable_annotations/102-type_checking.py) - Use mypy to validate the following piece of code and apply any necessary changes.
```
def zoom_array(lst: Tuple, factor: int = 2) -> Tuple:
    zoomed_in: Tuple = [
        item for item in lst
        for i in range(factor)
    ]
    return zoomed_in


array = [12, 72, 91]

zoom_2x = zoom_array(array)

zoom_3x = zoom_array(array, 3.0)
```
