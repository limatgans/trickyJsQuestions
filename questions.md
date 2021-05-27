Q: What is output of ```console.log(3>2>1)```?

A: false

Q: What is output of ```console.log(3<2<1)```?

A: True

**Explanation**: 

In JavaScript ```3>2>1``` will be evaluated in the following sequence:

```(3 > 2) > 1``` // same operator (>), will be evaluated from left to right

To `true > 1`

To `1 > 1` // coerced true to 1

To `false`
