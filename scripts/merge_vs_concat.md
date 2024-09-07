### Terraform `concat` Function

The `concat` function is used to concatenate multiple lists into a single list. The syntax is:

```hcl
concat(list1, list2, ...)
```



- **list1, list2, ...**: The lists you want to concatenate.

For example, `concat(["a", "b"], ["c", "d"])` would result in `["a", "b", "c", "d"]`.
