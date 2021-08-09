# Stream



### Float Field Flag

The floatfield format flag is both a selective and a toggle flag: it can take any of the following values, or none:

| Flag value | Effect when set |
| :--- | :--- |
| [fixed](../library/ios.md#fixed-and-scientific) | write floating-point values in fixed-point notation. |
| [scientific](../library/ios.md#fixed-and-scientific) | write floating-point values in scientific notation. |
| [hexfloat](../library/ios.md#hexfloat-and-defaultfloat) | write floating-point values in hexadecimal format.  The value of this is the same as `(fixed|scientific)` |
| [defaultfloat](../library/ios.md#hexfloat-and-defaultfloat) | write floating-point values in default floating-point notation. This is the value by default \(same as none, before any other floatfield bit is set\). |

  
 For standard streams, the floatfield format flag is set to [defaultfloat](../library/ios.md#hexfloat-and-defaultfloat) on initialization.  


