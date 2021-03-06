# Numerics

Tests the various instantiations and functions on the numeric data types.

## Source
See [Numerics.java](../../../bytecode/DataTypes/Numerics.java)

## Output

| Type | init | += | *= | >> | ==* | <=* |
| --- | --- | --- | --- | --- | --- | --- |
| int    | 2 | 4 | 4 | 4 | 3 | 4 |
| short  | 2 | 5 | 5 | - | 3 | 4 |
| long   | 2 | 4 | 4 | 4 | 4 | 5 |
| byte   | 2 | 5 | 5 | - | 3 | 4 |
| float  | 2 | 4 | 4 | - | 4 | 4 |
| double | 2 | 4 | 4 | - | 4 | 4 |

* On average, see details (here)[numerics_comparisons.md]

## Conclusion
Try and use int's for everything!
