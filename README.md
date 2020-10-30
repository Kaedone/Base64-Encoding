# Base64-Encoding
Extend the String object (JS) or create a function (Python, C#) that converts the value of the String to and from Base64 using the ASCII (UTF-8 for C#) character set.
Do not use built in functions.

# Usage
```JS
  // should return 'dGhpcyBpcyBhIHN0cmluZyEh'
  'this is a string!!'.toBase64(); 

  // should return 'this is a string!!'
  'dGhpcyBpcyBhIHN0cmluZyEh'.fromBase64(); 
```

Note: This kata uses the non-padding version ("=" is not added to the end).
