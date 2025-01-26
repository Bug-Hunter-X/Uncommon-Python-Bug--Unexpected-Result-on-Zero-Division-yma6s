# Uncommon Python Bug: Unexpected Result on Zero Division

This repository demonstrates a subtle bug in Python that doesn't raise an error but produces an unexpected result.

The `function_with_uncommon_error` function aims to handle the case where either `a` or `b` is zero. However, if both `a` and `b` are zero, it returns zero instead of raising a `ZeroDivisionError`.  This behavior might be unexpected and lead to hidden bugs in larger programs.

## How to Reproduce

1. Clone the repository.
2. Run `bug.py`.
3. Observe the unexpected result.