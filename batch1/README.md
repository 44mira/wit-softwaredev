# BATCH 1

## 1. Stop Spinning My Words (10pts)

Write a function that takes in a string of one or more words, and returns the same string, but with all words that have five or more letters reversed (Just like the name of this Kata). Strings passed in will consist of only letters and spaces. Spaces will be included only when more than one word is present.

Example:

```
"Hey fellow warriors"  --> "Hey wollef sroirraw" 
"This is a test        --> "This is a test" 
"This is another test" --> "This is rehtona test"
```

## 2. Find the odd int (20pts)

Given an array of integers, find the one that appears an odd number of times.

There will always be only one integer that appears an odd number of times.

`[7]` should return 7, because it occurs 1 time (which is odd).
`[0]` should return 0, because it occurs 1 time (which is odd).
`[1,1,2]` should return 2, because it occurs 1 time (which is odd).
`[0,1,0,1,0]` should return 0, because it occurs 3 times (which is odd).
`[1,2,2,3,3,3,4,3,3,3,2,2,1]` should return 4, because it appears 1 time (which is odd).

## 3. Digital Roots (25pts)

Digital root is the recursive sum of all the digits in a number.

Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.

Example: 
```
    16  -->  1 + 6 = 7
   942  -->  9 + 4 + 2 = 15  -->  1 + 5 = 6
132189  -->  1 + 3 + 2 + 1 + 8 + 9 = 24  -->  2 + 4 = 6
493193  -->  4 + 9 + 3 + 1 + 9 + 3 = 29  -->  2 + 9 = 11  -->  1 + 1 = 2
```
