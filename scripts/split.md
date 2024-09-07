### Terraform `split` Function

The `split` function in Terraform is used to break a string into a list of strings based on a specified delimiter. The syntax is:

```hcl
split(delimiter, string)
```

- **delimiter**: A string that specifies where to split the input string.
- **string**: The input string to be split.

For instance, `split("_", "abc_def_ghi")` would return a list `["abc", "def", "ghi"]`.
