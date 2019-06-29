# Arithmetic Expression Trees

Arithmetic expression trees are mathematical expressions represented
through their order of operations hierarchy. In this case, we've
represented several possible scenarios in XML files:

## Expected Behavior

| Name | Description | Result |
|------|-------------|--------|
| [All Safe Operators](all-safe-operations-tree.xml) | Tests for all arithmetic operations (+, -, \*, /) | 16 |
| [Integer Overflow](int-overflow-tree.xml) | Tests for values outside of the positive integer range (2^32) | 33157157166001 |
| [Single Value](single-value-tree.xml) | Tests for a single node tree | 25 |

## Expected Errors

- [Divide by Zero](divide-by-zero-tree.xml)
- [Negative Subtraction](negative-subtraction-tree.xml)
