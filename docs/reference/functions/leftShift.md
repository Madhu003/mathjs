# Function leftShift

Bitwise left logical shift of a value x by y number of bits, `x << y`.
For matrices, the function is evaluated element wise.
For units, the function is evaluated on the best prefix base.


## Syntax

```js
math.leftShift(x, y)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; BigNumber &#124; Boolean &#124; String &#124; Array &#124; Matrix &#124; null | Value to be shifted
`y` | Number &#124; BigNumber &#124; Boolean &#124; String &#124; null | Amount of shifts

### Returns

Type | Description
---- | -----------
Number &#124; BigNumber &#124; Array &#124; Matrix | `x` shifted left `y` times


## Examples

```js
math.leftShift(1, 2);               // returns Number 4

math.leftShift([1, 2, 3], 4);       // returns Array [16, 32, 64]
```


## See also

[bitAnd](bitAnd.md),
[bitNot](bitNot.md),
[bitOr](bitOr.md),
[bitXor](bitXor.md),
[rightArithShift](rightArithShift.md),
[rightLogShift](rightLogShift.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->