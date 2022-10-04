# float-art
allow float to perform arithmetical operation of multiplication and addition without returning multiple decimals.
# float-art
A beautiful method to perform float arithemtics
# Installation 
```ja
$npm install float-art
```
# Features
- returns accurate solution for float multiplication 
- returns accurate solution for float addition
- can perform for both float and numbers without limitations
# Usage 
The float-art is very easy to use. It has two core methods of basic arithmetics : `number.multiply() `and 
` number.add ()`. 
These methods takes float and number expressions as arguments in the functions.
## Getting basic float-art informations
lets dive into a simple `examples/test_art.js`
```javascript
var number = require('float-art');
// number can be any variable

var ans = number.multiply(0.2 , 0.1 , 0.91);
var num = number.add(0.2 , 0.1 , 0.91);
console.log(num);
console.log(ans);
```
This will be the result following command-line output: 
```javascript
$ node examples/test_art.js
0.0182
1.21
```





