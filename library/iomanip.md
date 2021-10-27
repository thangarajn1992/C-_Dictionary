# iomanip

This header file provides parametric manipulators such as:

* setiosflags
* resetiosflags
* setbase
* setfill
* setprecision
* setw
* get\_money
* put\_money
* get\_time
* put\_time

### setiosflags



### resetiosflags



### setbase



### setfill



### setprecision

Sets the decimal precision to be used to format floating-point values on output operations.\
Behaves as if member [precision](http://www.cplusplus.com/ios\_base::precision) were called with n as argument on the stream on which it is inserted/extracted as a manipulator (it can be inserted/extracted on [input streams](http://www.cplusplus.com/basic\_istream) or [output streams](http://www.cplusplus.com/basic\_ostream)).

```cpp
// setprecision example
#include <iostream>     // std::cout, std::fixed
#include <iomanip>      // std::setprecision

int main () {
  double f =3.14159;
  // Without fixed, the parameter '5' denotes the number of valid digits
  // on both before and after decimal point
  std::cout << std::setprecision(5) << f << '\n';
  std::cout << std::setprecision(9) << f << '\n';
  
  // With fixed, the parameter '5' denotes the number of valid digits 
  // after the decimal point.
  std::cout << std::fixed;
  std::cout << std::setprecision(5) << f << '\n';
  std::cout << std::setprecision(9) << f << '\n';
  return 0;
}

Output:
3.1416
3.14159
3.14159
3.141590000
```

### setw



### get\_money



### put\_money



### get\_time



### put\_time



