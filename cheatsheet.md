# My Cheatsheet

## Syntax

**1. Count rows per group**

```python
df.groupby('prompt_id').size()
```

Note: groupby puts rows into buckets, size counts each bucket.

**1. Applying Function only on col**

```python
train["new_col"] = train["col"].apply(function)
```

Note: runs your function on every row of that column, and the results go into a new column.

## Errors
