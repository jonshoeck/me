# Personal JavaScript Style Guide

# Introduction
This guide is intended to be used as a style reference for Qualcomm developers writing JavaScript code. 
For updates or questions contact Jon. 

# Basic Syntax
```javascript
//
// Use this function to get the max value from an array.
//
// @param arr the array you want the max value of
// @returns   the max value if found, undefined if not
//
function getMax(arr) {
  // make sure the array provided is valid
  if (!Array.isArray(arr) || (arr.length < 1)) {
    return;
  }
  
  // check each element in the array to find the new max
  var max = arr[0];
  arr.forEach(function(ele){
    if (ele > max) {
      max = ele;
    }
  });
  
  // return the max value
  return max;
}
```
Note that:
- Comments are used to preface functions and group code
- Indents are two spaces
- Semicolons (while optional) should be used
- Opening brackets should be placed on the same line
- Closing brackets should be placed on their own line
- Comment blocks use ```//``` instead of ```/* */```

# Comments
```javascript
//
// functionName()
// Short description of the function and what it does
// 
// Inputs: 
//   - param #1: brief description of param #1
//   - param #2, brief description of param #2
// Returns:
//   - return value of the function 
//
function add2(num) {
  return num + 2;
}
```

# Naming Conventions
- filenames 
- variables
- functions
- classes
## Filenames 
## Variables
## Functions
## Classes

# Return Codes
