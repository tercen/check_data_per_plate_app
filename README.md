# check_data_per_plate_app

##### Description

`check_data_per_plate_app` is an application that checks if each well in a group has 0 or 1 data points and flags those that have more.

##### Details

The input data is the [c04_groups](https://github.com/tercen/data_designs/tree/main/c04_groups)

This workflow has 3 operators:

* [replace (1.1.0)](https://github.com/tercen/replace_operator/tree/0.1.1)
* [count (0.11.1)](https://github.com/tercen/count_operator/tree/0.11.1)
* [flag (0.3.4)](https://github.com/tercen/flag_operator/tree/0.3.4)

##### See Also
