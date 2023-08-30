# Matching an Hexadecimal Regex by Hung Quoc Dang

Introductory paragraph (replace this with your text)

## Summary

This tutorial shows the code snippet will filter out a validated Hexadecimal string of 2 and 4 digits, the strings entered by users can have any alphanumeric and any special characters:

^([a-fA-F0-9]{4}|[a-fA-F0-9]{2})$

The testing of this snippet can be done with https://regex101.com/ ; using flavor ECMASript(javaS…

A valid Hexadecimal digit must be one of these: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F and the letters can be minuscule or majuscule.



## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

### Anchors

The anchors are used in defining the Regex snippets, the ^ and $ are to be put at the beginning and the end of the snippet.

This ^ asserts that the pattern must match the start of the string. This $ asserts that the pattern must match the end of the string.

### Quantifiers

The quantifiers are used by { } where element inside the curly parenthesis is an integer value indicating the desired number of digits forming a valid Hexadecimal string.

### Grouping Constructs

Grouping-constructs or subexpression are  ( ) inside the code snippets.  Where the pattern of characters inside the ( ) is set for exactly matching with a presented character string.

### Bracket Expressions

Bracket Expressions uses [  ], elements inside the  [  ]  specify how the target string needs to be matched  based on any order indicating inside the [  ].


### The OR Operator

Here the Boolean OR logic uses | in the snippet.  So, this snippet the | is to filter out either 4 or 2 consecutive characters of validated Hexadecimal string.

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)


The usefulness of this ^([a-fA-F0-9]{4}|[a-fA-F0-9]{2})$ is for a user to enter a set of characters that need to be valid Hexadecimal of 2 or 4 digits where a converter of Hexadecimal to binary values that will show what are the 8 bits that supposed to be set in a RAM or 16 bits that are supposed to be set in a register.  One Hexadecimal has 4 binary bits.