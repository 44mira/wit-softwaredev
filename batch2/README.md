# BATCH 2

## 1. Break camelCasing (15pts)

Create a function will break up camel casing, using a space between words.

Examples:

```
"camelCasing"  =>  "camel Casing"
"identifier"   =>  "identifier"
""             =>  ""
```

## 2. RGB to Hex (15pts)

Take an input of 3 numbers (each being 0-255), and convert it to its corresponding Hex value. Overflowed numbers will be bounded by its closest bound. (< 0 will be `00` and > 255 would be `FF`).

Examples:

```
255, 255, 255 --> "FFFFFF"
255, 255, 300 --> "FFFFFF"
0, 0, 0       --> "000000"
148, 0, 211   --> "9400D3"
```

## 3. First non-repeating character (20pts)

Write a function that takes a string input, and returns the first character that is not repeated anywhere in the string.

For example, if given the input 'stress', the function should return 't', since the letter t only occurs once in the string, and occurs first in the string.

As an added challenge, upper- and lowercase letters are considered the same character, but the function should return the correct case for the initial letter. For example, the input 'sTreSS' should return 'T'.

If a string contains all repeating characters, it should return an empty string ("")
