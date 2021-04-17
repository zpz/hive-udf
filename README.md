# hive-udf

Hive UDF (user-defined functions) in Python.

Reference: [blog post](https://zpz.github.io/blog/hive-udf/).

This package provides a single function `make_udf` for
working with Hive UDF written in Python.
Please see source code for documentation.

Several example UDF modules are included, and can be used for tests.
Because real tests need a Hive setup, they are not performed here.
User may test this package in their own Hive envivonrment, using
the few example UDFs.
The blog post offers some ideas about testing as well.

This package is ready for production use.