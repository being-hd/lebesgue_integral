### Computing Lebesgue Integral

This is a simple Python implementation of the Lebesgue Integral using first principles. Not many examples are available that discuss the method of computing Lebesgue integral using first principles. In this context, the python notebook will be useful for a conceptual understanding of Lebesgue integral in R by computing measures of pre-image sets.
<br>
The code has scope for improvements but neverthess it will serve as an excellent starting point.

### Example:

```python
obj = lebesgue_integral('x^2', 0, 1)
obj.integral_value()
```
### Output:
```python
Upper Lebesgue sum UL(100) = 0.338589
Lower Lebesgue sum LL(100) = 0.328588
Integral is: 0.333588
```
In the example, `n=100` where `n` is the number of partition points.