## 1. mising variable name

-broken code:
```js
var = 5;
```
-error message:
```js
SyntaxError: Unexpected token =
```

classification:
Creation phase
Syntax

-the fix:
```js
var x = 5
```

your notes:
A variable is missing a name. This is likely due to a syntax error in your code. You struggled with coming up with a name. Totally understandable! Naming things is so hard.

---

## 2. too-far object access
broken code:
```js
let a = {b:3};
let b = a.b.3
```
error message:
```js
SyntaxError: Unexpected number
```
classification:
* creation phase
* syntax

the fix:
```js
let a = {b:3};
let b = a.b;3
```
your notes:
number 3 is not necessary because it's already declared in the previous code let a = {b:3}

---
## 3. access property directly
broken code:
```js
let x = {b:'e'};
let y = b.e;
```
error message:
```js
SyntaxError: Unexpected end of input
```
classification:
* creation phase
* syntax

the fix:
```js
let x = {b:'e'};
let y = x;
```
your notes:
To tell that y has the same value as x
always indent your code (and indent it correctly)

---

## 4. improper multi-line string
broken code:
```js
let a = 'this is 
two lines';
```
error message:
```js
SyntaxError: Unexpected token ILLEGAL
```
classification:
* creation phase
* syntax

the fix:
```js
let a = 'this is\ntwo lines'
```
your notes:

---
## 5. improper end of statement
broken code:
```js
let a = 1:
```
error message:
```js
SyntaxError: Unexpected token :
```
classification:
* creation phase
* syntax

the fix:
```js
let a = 1;
```
your notes:
end of statement use this ';'

---
## 6. malformed array
broken code:
```js
let myArray = [1, 2, 3;
```
error message:
```js
SyntaxError: Unexpected token ;
```
classification:
* creation phase
* syntax

the fix:
```js
let myArray = [1, 2, 3];
```
your notes:

---
## 7. missing arguments
broken code:
```js
function getNine {
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
error message:
```js
SyntaxError: Unexpected token function
```
classification:
* creation phase
* syntax 

the fix:
```js
function getNine () {
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
your notes:
Brackets for param is missing

---
## 8. improper nested quotes 1
broken code:
```js
let innerHtml = "<p>Click here to <a href="#Home">return home</a></p>";
```
error message:
```js
SyntaxError: Unexpected token ILLEGAL
```
classification:
* creation phase
* syntax

the fix:
```js
let innerHtml = '<p>Click here to <a href="#Home">return home</a></p>';

```
your notes: 

---
## 9. improper nested quotes 2 
broken code:
```js
let nested_messages = 'remind yourself ''i can do this!'' at least once a day';
```
error message:
```js
SyntaxError: Unexpected string
```
classification:
* creation phase
* syntax

the fix:
```js
let nested_messages = 'remind yourself \'i can do this\'at least once a day';
```
your notes:

---
## 10. reassigning to constant
broken code:
```js
const a = 9;
a = 0;
```
error message:
```js
typeError: Assignment to constant variable.
```
classification:
* execution phase
* semantic

the fix:
```js
const a = 9;
```
your notes:

---
## 11. unassigned const declaration
broken code:
```js
const a;
a = 0;
```
error message:
```js
SyntaxError: Missing initializer in const declaration
```
classification:
* creation phase
* syntax

the fix:
```js
const a = 0;
```
your notes:
Must specify it's value in the same statement in that is declared 

---
## 12. is not a function
broken code:
```js
let array = [];
array.length()
```
error message:
```js
TypeError: array.length is not a function
```
classification:
* execution phase ?
* semantic ?

the fix:
```js
let array = [];
array.length;
```
your notes:

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
