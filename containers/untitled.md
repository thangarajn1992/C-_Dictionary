# Stream

 The floatfield format flag is both a selective and a toggle flag: it can take any of the following values, or none:  
  


| flag value | effect when set |
| :--- | :--- |
| fixed | write floating-point values in fixed-point notation. |
| [scientific](http://www.cplusplus.com/scientific) | write floating-point values in scientific notation. |
| [hexfloat](http://www.cplusplus.com/hexfloat) | write floating-point values in hexadecimal format.  The value of this is the same as `(fixed|scientific)` |
| [defaultfloat](http://www.cplusplus.com/defaultfloat) | write floating-point values in default floating-point notation. This is the value by default \(same as none, before any other floatfield bit is set\). |

  
 For standard streams, the floatfield format flag is set to [defaultfloat](http://www.cplusplus.com/defaultfloat) on initialization.  


