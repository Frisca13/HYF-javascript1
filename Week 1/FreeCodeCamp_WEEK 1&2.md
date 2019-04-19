Exercise 1 JS

## 1. How to write comments
```js
//abcde//
/*abcde*/
```
I know how to write comments

## 2. Declare JavaScript Variables
```js
// Example
var ourName;

// Declare myName below this line
var myName;
```

## 3. Storing Values with the Assignment Operator
```js
// Setup
var a;
var b = 2;

// Only change code below this line
var a = 7;
var b = 7;
b = a;
```

## 4. Initializing Variables with the Assignment Operator
```js
// Example
var ourVar = 19;

// Only change code below this line
var a = 9;
```

## 5. Understanding Uninitialized Variables
```js
// Initialize these three variables
var a = 5;
var b = 10;
var c = 'I am a';

// Do not change code below this line

a = a + 1;
b = b + 5;
c = c + " String!";
```

## 6. Understanding Case Sensitivity in Variables
```js
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
var studlyCapVar = 10;
var properCamelCase = "A String";
var titleCaseOver = 9000;
```

## 7. Add Two Numbers with JavaScript
```js
var sum = 10 + 10;
```

## 8. Subtract One Number from Another with JavaScript
```js
var difference = 45 - 33;
```

## 9. Multiply Two Numbers with JavaScript
```js
var product = 8 * 10;
```

## 10. Divide One Number by Another with JavaScript
```js
var quotient = 66 / 33;
```

## 11. Increment a Number with JavaScript
```js
var myVar = 87;

// Only change code below this line
var myVar = 87;myVar++;
```

## 12. Decrement a Number with JavaScript
```js
var myVar = 11;

// Only change code below this line
var myVar = 1
```

## 13. Create Decimal Numbers with JavaScript
```js
var ourDecimal = 5.7;

// Only change code below this line
var myDecimal = 5.7;
```

## 14. Multiply Two Decimals with JavaScript
```js
var product = 2.0 * 0.0;
//my fix//
var product = 1.0 * 5.0;
```

## 15. Divide One Decimal by Another with JavaScript
```js
var quotient = 4.4 / 2.0
```

## 16. Finding a Remainder in JavaScript
```js
// Only change code below this line

var remainder = 11 % 3;
```

## 17. Compound Assignment With Augmented Addition
```js
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a += 12;
b += 9;
c += 7;
```

## 18. nted Subtraction
```js
var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a -= 6;
b -= 15;
c -= 1;
```

## 19. Compound Assignment With Augmented Multiplication
```js
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a *= 5;
b *= 3;
c *= 10;
```

## 20. Compound Assignment With Augmented Division
```js
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a /= 12;
b /= 4;
c /= 11;
```

## 21. Declare String Variables
```js
// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line
var myFirstName = "Frisca"
var myLastName = "Julia"
```

## 22. Escaping Literal Quotes in Strings
```js
var myStr = "I am a \"double quoted\" string inside \"double quotes\".";
```

## 23. Quoting Strings with Single Quote
```js
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

## 34. Escape Sequences in Strings
```js
var myStr = "FirstLine\n\t\\"+"SecondLine\n"+"ThirdLine";
```

## 35. Concatenating Strings with Plus Operator
```js
// Example
var ourStr = "I come first. ";
ourStr += "I come second.";

// Only change code below this line

var myStr = "This is the first sentence. " ;
myStr += "This is the second sentence.";
````

## 26. Constructing Strings with Variables
```js
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";

// Only change code below this line
var myName = "Frisca ";
var myStr = "My name is " + myName + " and I am well!";
```

## 27. Appending Variables to Strings
```js
// Example
var anAdjective = "awesome!";
var ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

// Only change code below this line

var someAdjective = "interesting" ;
var myStr = "Learning to code is";
myStr += someAdjective;
```

## 28. Find the Length of a String
```js
// Example
var firstNameLength = 0;
var firstName = "Ada";

firstNameLength = firstName.length;

// Setup
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.

lastNameLength = 8;
lastName = "Cordelia";

lastNameLength = lastName.length;
```

## 29. Use Bracket Notation to Find the First Character in a String
```js
// Example
var firstLetterOfFirstName = "";
var firstName = "Ada";

firstLetterOfFirstName = firstName[0];

// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";

// Only change code below this line
var firstLetterOfLastName = "";
var lastName = "L";

firstLetterOfLastName = lastName[0];
```

## 30. Understand String Immutability
```js
// Setup
var myStr = "Jello World";

// Only change code below this line

var myStr = "Jello World"
myStr= "H";
myStr = "Hello World";
```

## 31. Use Bracket Notation to Find the Nth Character in a String
```js
// Example
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var thirdLetterOfLastName = "V";
var thirdLetterOfLastName = lastName[2];
var lastName = "Lovelace";
```

## 32. Use Bracket Notation to Find the Last Character in a String
```js
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = "e";
var lastLetterOfLastName = lastName[lastName.length -1];
var lastName = "Lovelace"
```

## 33. Use Bracket Notation to Find the Nth-to-Last Character in a String
```js
// Example
var firstName = "Ada";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];

// Setup
var lastName = "Lovelace";

// Only change code below this line
var secondToLastLetterOfLastName = "c";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];

var lastName = "Lovelace";
```

## 34. Word Blanks
```js
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Your code below this line
  var result = "";
result+= "My "+myAdjective+" "+myNoun+" "+myVerb+" very "+myAdverb+".";
  // Your code above this line
  return result;
}

// Change the words here to test your function
wordBlanks("dog", "big", "ran", "quickly");
```

## 35. Store Multiple Values in one Variable using JavaScript Arrays
```js
// Example
var ourArray = ["John", 23];

// Only change code below this line.
var myArray = ["array", 13];
```

## 36. Nest one Array within Another Array
```js
// Example
var ourArray = [["the universe", 42], ["everything", 101010]];

// Only change code below this line.
var myArray = [["Bulls",23], ["White Sox", 45]];
```

## 37. Access Array Data with Indexes
```js
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50

// Setup
var myArray = [50,60,70];

// Only change code below this line.
var myArray = [50,60,70];
var myData = myArray[0];

var myArray = [50,60,70];
```

## 38. Modify Array Data With Indexes
```js
// Example
var ourArray = [18,64,99];
ourArray[1] = 45; // ourArray now equals [18,45,99].

// Setup
var myArray = [18,64,99];

// Only change code below this line.
var myArray = [18,64,99];
myArray[0] = 45;
var myArray = [45,64,99];
```

## 39. Access Multi-Dimensional Arrays With Indexes
```js
// Setup
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

// Only change code below this line.
var myData = myArray[2][1];
```

## 40. Manipulate Arrays With push()
```js
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.push(["happy", "joy"]);
// ourArray now equals ["Stimpson", "J", "cat", ["happy", "joy"]]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
myArray.push(["dog", 3]);
```

## 41. Manipulate Arrays With pop()
```js
// Example
var ourArray = [1,2,3];
var removedFromOurArray = ourArray.pop(); 
// removedFromOurArray now equals 3, and ourArray now equals [1,2]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
var removedFromMyArray = myArray.pop();
```

## 42. Manipulate Arrays With shift()
```js
// Example
var ourArray = ["Stimpson", "J", ["cat"]];
var removedFromOurArray = ourArray.shift();
// removedFromOurArray now equals "Stimpson" and ourArray now equals ["J", ["cat"]].

// Setup
var myArray = [["John", 23], ["dog", 3]];

// Only change code below this line.
var removedFromMyArray = myArray.shift();
```

## 43. Manipulate Arrays With unshift()
```js
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();

myArray.unshift(["Paul",35])
```

## 44. Shopping List
```js
var myList = [["rice", 5] , ["bread", 6] , ["cake", 7], [ "quinoa", 9], ["potato", 20]];
```

## 45. Write Reusable JavaScript with Functions
```js
function reusableFunction() {
  console.log("Hi World");
}

reusableFunction();
```

## 47.Passing Values to Functions with Arguments
```js
// Example
function ourFunctionWithArgs(a, b) {
  console.log(a - b);
}
ourFunctionWithArgs(10, 5); // Outputs 5

// Only change code below this line.
function functionWithArgs (a , b) {
console.log(a + b);
}
functionWithArgs (1 , 2);
functionWithArgs (7 , 9);
```
## 48. Global Scope and Functions
```js
// Declare your variable here


function fun1() {
  // Assign 5 to oopsGlobal Here
  
}

// Only change code above this line
function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
var myGlobal = 10;
function fun1() {
  oopsGlobal = 5;
}
```

## 49. Local Scope and Functions
```js
function myLocalScope() {
var myVar = 'use strict';
}
myLocalScope();
```

## 50. Global vs. Local Scope in Functions
```js
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  
  
  
  // Only change code above this line
  return outerWear;
}

myOutfit();
var outerWear = "T-Shirt";
function myOutfit() {
  var outerWear = "sweater";
  return outerWear;
}
myOutfit();
```

## 51. Return a Value from a Function with Return
```js
// Example
function minusSeven(num) {
  return num - 7;
}

// Only change code below this line
function timesFive (num) {
  return num * 5;
}
timesFive(5);
timesFive(2);
timesFive(0);


console.log(minusSeven(10));
```

## 52. Understanding Undefined Value returned from a Function
```js
// Example
var sum = 0;
function addThree() {
  sum = sum + 3;
}

// Only change code below this line



// Only change code above this line
var returnedValue = addFive();
function addFive() {
  sum = sum + 5;
}
```

## 53. Assignment with a Returned Value
```js
// Example
var changed = 0;

function change(num) {
  return (num + 5) / 3;
}

changed = change(10);

// Setup
var processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
var processed = 0;
function processArg(num) {
  return (num + 3) / 5;
}
processed = processArg(7);
```

## 54. Stand in Line
```js
function nextInLine(arr, item) {
  // Your code here
    arr.push(item);
    return  arr.shift();   // Change this line
}

// Test Setup
var testArr = [1,2,3,4,5];

// Display Code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 10) ,testArr[4]); // Modify this line to test
console.log("After: " + JSON.stringify(testArr));
```

## 55. Understanding Boolean Values
```js
function welcomeToBooleans() {
return true;
}
```

## 56. Use Conditional Logic with If Statements
```js
// Example
function ourTrueOrFalse(isItTrue) {
  if (isItTrue) { 
    return "Yes, it's true";
  }
  return "No, it's false";
}

// Setup
function trueOrFalse(wasThatTrue) {

  // Only change code below this line.

    if (wasThatTrue) {
    return "Yes, that was true";
  }
  return "No, that was false";
}

  // Only change code above this line.
// Change this value to test
trueOrFalse(true);
```

## 57. Comparison with the Equality Operator
```js
// Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testEqual(12);
```

## 58. Comparison with the Strict Equality Operator
```js
// Setup
function testStrict(val) {
  if (val === 7) {// Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testStrict(10);
```

## 59. Practice comparing different values
```js
// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
compareEquality(10, "10")
```

## 60. Comparison with the Inequality Operator
```js
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(10);
```

## 61. Comparison with the Strict Inequality Operator
```js
// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val !== 17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```

## 62. Comparison with the Greater Than Operator
```js
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

// Change this value to test
testGreaterThan(10);
```

## 63. Comparison with the Greater Than Or Equal To Operator
```js
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }
  
  if (val >= 10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

// Change this value to test
testGreaterOrEqual(10);
```

## 64. Comparison with the Less Than Operator
```js
function testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }
  
  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

// Change this value to test
testLessThan(10);
```

## 65. Comparison with the Less Than Or Equal To Operator
```js
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }
  
  if (val <= 24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

// Change this value to test
testLessOrEqual(10);
```

## 66. Comparisons with the Logical And Operator
```js
function testLogicalAnd(val) {
  // Only change code below this line
  if (val >= 25 && val <= 50) {
      return "Yes";
  }

  // Only change code above this line
  return "No";
}

// Change this value to test
testLogicalAnd(10);
```

## 67. Comparisons with the Logical Or Operator
```js
function testLogicalOr(val) {
  // Only change code below this line

  if (val < 10 || val > 20 ) {

    return "Outside";
;
}

  // Only change code above this line
  return "Inside";
}

// Change this value to test
testLogicalOr(15);
```

## 68. Introducing Else Statements
```js
function testElse(val) {
  var result = "";
  // Only change code below this line

  if (val > 5) {
    result = "Bigger than 5";
  }

  else {
    result = "5 or Smaller";
  }
  
  // Only change code above this line
  return result;
}

// Change this value to test
testElse(4);
```

## 69. Introducing Else If Statements
```js
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }

  else if (val < 5) {
    return "Smaller than 5";
  }
  else {
      return "Between 5 and 10";
  }

}

testElseIf(7);
```

## 70. Logical Order in If Else Statements
```js
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}

orderMyLogic(7);
```

## 71. Chaining If Else Statements
```js
function testSize(num) {
  // Only change code below this line
  if(num < 5) {
    return "Tiny";
  } else if (num < 10) {
 return "Small";
  } else if (num < 15) {
return "Medium";
  } else if (num < 20) {
return "Large";
  } else if ( num >= 20 ) {
    return "Huge";
    } else {
    return "Change Me"; }

}
  // Only change code above this line
// Change this value to test
testSize(7);
```

## 72. Golf Code
```js
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  if (strokes == 1) {
return "Hole-in-one!";
  } else if (strokes <= par - 2) {
     return "Eagle" ;
  } else if (strokes == par - 1) {
     return "Birdie" ;
  } else if (strokes == par) {
     return "Par" ;
  } else if (strokes == par + 1) {
     return "Bogey" ;
  } else if (strokes == par + 2) {
     return "Double Bogey" ;
  } else if (strokes >= par + 3) {
     return "Go Home!" ;
  } else {
     return "Change Me";
  }
}

golfScore(5, 4);
```

# WEEK 2

## 73. Selecting from Many Options with Switch Statements
```js
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
  case 1:
    return "alpha";
    break;
  case 2:
    return "beta";
    break;
  case 3:
    return "gamma";
    break;
     case 4:
   return "delta";
    break;
}
  // Only change code above this line  
  return answer;  
}

// Change this value to test
caseInSwitch(1);
caseInSwitch(2);
caseInSwitch(3);
caseInSwitch(4);
```

## 74. Adding a Default Option in Switch Statements
```js
function switchOfStuff(val) {
  var answer = "";
    switch(val) {
  case "a":
    answer = "apple";
    break;
  case "b":
    answer = "bird";
    break;
  case "c":
    answer = "cat";
    break;
  default:
   answer = "stuff";
}

  return answer;
}

switchOfStuff(1);
```

## 75. Multiple Identical Options in Switch Statements
```js
 function sequentialSizes(val) {
  var answer = "";
  switch(val) {
  case 1:
  case 2:
  case 3:
    answer = "Low";
    break;
  case 4:
  case 5:
  case 6:
    answer = "Mid";
    break;
  case 7:
  case 8:
  case 9:
    answer = "High";
}
  return answer;
}

sequentialSizes(1);

```

## 76. Replacing If Else Chains with Switch
```js
function chainToSwitch(val) {
  var answer = "";

  switch(val) {
  case "bob":
    answer = "Marley";
    break;
  case 42:
    answer = "The Answer";
    break;
  case 1:
    answer = "There is no #1";
    break;
  case 99:
    answer = "Missed me by this much!";
    break;
  case 7:
    answer = "Ate Nine";
    break;
  default:
    answer = "";
    break;
}

  return answer;
}

chainToSwitch(7);
```

## 77. Returning Boolean Values from Functions
```js
function isLess(a, b) {
  // Fix this code

  return a < b;
}

// Change these values to test
isLess(10, 15);
```

## 78. Return Early Pattern for Functions
```js
function abTest(a, b) {
 if (a < 0 || b < 0) {
   return undefined;
 }else{
  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}

}
abTest(2,2);
```

## 79. Counting Cards
```js
var count = 0;
function cc(card) {
switch(card){
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
      count++;
      break;
    case 10:
    case "J":
    case "Q":
    case "K":
    case "A":
      count--;
      break;
  }
  if (count > 0){
    return count + " Bet";
  } else {
    return count + " Hold";
  }
}var count = 0; 

cc(2); cc(3); cc(7); cc('K'); cc('A');
```

## 80. Build Javascript Object
```js
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};

// Only change code below this line.

var myDog = {
    "name": "Brownie",
  "legs": 4,
  "tails": 1,
  "friends": ["me"]
};
```

## 81. Accessing Object Properties with Dot Notation
```js
var testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};

var hatValue = testObj.hat;
var shirtValue = testObj.shirt;
```

## 82. Accessing Object Properties with Bracket Notation
```js
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};
var entreeValue = testObj["an entree"];
var drinkValue = testObj["the drink"];
```

## 83. Accessing Object Properties with Variables
```js
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};
var playerNumber = 16;
var player = testObj[playerNumber];
```

## 84. Updating Object Properties
```js
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};
myDog.name = "Happy Coder";
```

## 85. Add New Properties to a JavaScript Object
```js
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};


myDog["bark"] = "woof";
```

## 86. Delete Properties from a JavaScript Object
```js
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"],
  "bark": "bow-wow"
};

delete ourDog.bark;

// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

// Only change code below this line.
delete myDog.tails;
```

## 87. Using Objects for Lookups
```js
function phoneticLookup(val) {
  var result = "";

  var lookup = {
 "alpha": "Adams",
  "bravo": "Boston",
  "charlie": "Chicago",
  "delta": "Denver",
  "echo": "Easy",
  "foxtrot": "Frank"
  };
  result = lookup[val];
  return result;
}

phoneticLookup("charlie");
```

## 88. Testing Objects for Properties
```js
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
 return myObj.hasOwnProperty(checkProp) ? myObj[checkProp]: "Not Found";
}

checkObj("gift");
```

## 89. Manipulating Complex Objects
```js
var myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  },
  {

   "artist": "JLO",
    "title": "Girl",
    "release_year": 1999,
    "formats": [
      "Vinnyl",
      "8T",
      "LP"
    ]
  }
];
```

## 90. Accessing Nested Objects
```js
// Setup
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

var gloveBoxContents = myStorage.car.inside["glove box"]; // Change this line
```

## 91. Accessing Nested Arrays
```js
// Setup
var myPlants = [
  { 
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }  
];

// Only change code below this line

var secondTree = myPlants[1].list[1]; // Change this line
```

## 92. Record Collection
```js
var collection = {
    "2548": {
      "album": "Slippery When Wet",
      "artist": "Bon Jovi",
      "tracks": [
        "Let It Rock",
        "You Give Love a Bad Name"
      ]
    },
    "2468": {
      "album": "1999",
      "artist": "Prince",
      "tracks": [
        "1999",
        "Little Red Corvette"
      ]
    },
    "1245": {
      "artist": "Robert Palmer",
      "tracks": [ ]
    },
    "5439": {
      "album": "ABBA Gold"
    }
};
// Keep a copy of the collection for tests
var collectionCopy = JSON.parse(JSON.stringify(collection));


function updateRecords(id, prop, value) {
  if (prop === "tracks" && value !== ""){
    if (collection[id][prop]){
      collection[id][prop].push(value);
    }else{
      collection[id][prop] = [value];
    }
  } else if (value !== "") {
     collection[id][prop] = value;
  } else {
    delete collection[id][prop];
  }
  return collection;
}
updateRecords(5439, "artist", "ABBA");
```

## 93. Iterate with JavaScript While Loops
```js
// Setup
var myArray = [];

// Only change code below this line.
var i = 0;
while(i <= 4) {
  myArray.push(i);
  i++;
}
```

## 94. Iterate with JavaScript For Loops
```js
// Example
var ourArray = [];

for (var i = 0; i < 5; i++) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (var i = 1; i <= 5; i++) {
    myArray.push(i);
}
```

## 95. Iterate Odd Numbers With a For Loop
```js
// Example
var ourArray = [];

for (var i = 0; i < 10; i += 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (var i = 1; i <= 9; i += 2){
  myArray.push(i);
}
```

## 96. Count Backwards With a For Loop
```js
// Example
var ourArray = [];

for (var i = 10; i > 0; i -= 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (var i = 9; i > 0; i -= 2){
  myArray.push(i);
}
```

## 97. Iterate Through an Array with a For Loop
```js
// Example
var ourArr = [ 9, 10, 11, 12];
var ourTotal = 0;

for (var i = 0; i < ourArr.length; i++) {
  ourTotal += ourArr[i];
}

// Setup
var myArr = [ 2, 3, 4, 5, 6];

// Only change code below this line
var total = 0;
for(var i = 0; i < myArr.length; i++){
  total += myArr[i];
}
```

## 98. Nesting For Loops
```js
function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
  for (var i=0; i < arr.length; i++) {
    for (var j=0; j < arr[i].length; j++) {
    product = product * arr[i][j];
    }
  }
  // Only change code above this line
  return product;
}

// Modify values below to test your code
multiplyAll([[1,2],[3,4],[5,6,7]]);
```

## 99. Iterate with JavaScript Do...While Loops
```js
var myArray = [];
var i = 10;

do {
 myArray.push(i);
  i++;
} while (i < 5);
```

## 100. Profile Lookup
```js
var contacts = [
    {
        "firstName": "Akira",
        "lastName": "Laine",
        "number": "0543236543",
        "likes": ["Pizza", "Coding", "Brownie Points"]
    },
    {
        "firstName": "Harry",
        "lastName": "Potter",
        "number": "0994372684",
        "likes": ["Hogwarts", "Magic", "Hagrid"]
    },
    {
        "firstName": "Sherlock",
        "lastName": "Holmes",
        "number": "0487345643",
        "likes": ["Intriguing Cases", "Violin"]
    },
    {
        "firstName": "Kristian",
        "lastName": "Vos",
        "number": "unknown",
        "likes": ["JavaScript", "Gaming", "Foxes"]
    }
];


function lookUpProfile(name, prop){
for(var i = 0; i < contacts.length; i++){
  var contact = contacts[i];
  if (contact.firstName === name){
    if(contact.hasOwnProperty(prop)){
      return contact[prop];
    }else {
      return "No such property";
    }
  }
}
return "No such contact";
}

lookUpProfile("Akira", "likes");
```

## 101. Generate Random Fractions with JavaScript
```js
function randomFraction() {

  // Only change code below this line.

  return Math.random();
}

  // Only change code above this line.
```

## 102. Generate Random Whole Numbers with JavaScript
```js
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);
function randomWholeNum() {
  return Math.floor(Math.random() * 10);
}
```

## 103. Generate Random Whole Numbers within a Range
```js
function randomRange(myMin, myMax) {
  return Math.floor(Math.random() * (myMax - myMin + 1)) + myMin;
}
var myRandom = randomRange(5, 15);
```

## 104. Use the parseInt Function
```js
function convertToInteger(str) {
  return parseInt(str);
}

convertToInteger("56");
```

## 105. Use the parseInt Function with a Radix
```js
function convertToInteger(str) {
  return parseInt(str, 2);
}

convertToInteger("10011");
```

## 106. Use the Conditional Ternary Operator
```js
function checkEqual(a, b) {
  return a === b ? true : false;
}

checkEqual(1, 2);
```

## 107. Use Multiple Conditional (Ternary) Operators
```js
function checkSign(num) {
  return num === 0 ? "zero" : num > 0 ? "positive" : "negative";
}

checkSign(10);
```
