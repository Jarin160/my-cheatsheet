# My Cheatsheet

## Pandas

**Count rows per group**

```python
df.groupby('prompt_id').size()
```

Note: groupby puts rows into buckets, size counts each bucket.

## Errors

**`name 'torch' is not defined`**
Cause: forgot `import torch` after a restart.
Fix: run the import cell first.
