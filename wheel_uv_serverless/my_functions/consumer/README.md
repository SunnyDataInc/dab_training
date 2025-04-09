# consumer package
This package depends on the `mymath` package, so make sure to add the following entry to the consumer's `pyproject.toml` file:
```
dependencies = [
    "mymath>=0.1.0",
]
```

This wheel contains two functions:
* **compute_sum_and_product**: it returns the addition and multiplication of two numbers.
* **combined_output**: it returns the results of `compute_sum_and_product` formatted in a message.