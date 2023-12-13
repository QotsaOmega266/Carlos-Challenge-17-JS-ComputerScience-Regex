# QotsaOmega266(Carlos Ogle) - Regex Tutorial

The goal in this project is to create a tutorial on regular expressions to hepl the user understand how they properly work and how to use them in their own coding applications. 

## Summary

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

The regular expression code above is used to match a hex value of 6 or 3 digit and characters using the logical OR. The code is made up of two segments seperated by the | symbol. 

[a-f0-9]{6} : This portion matches a sequence of 6 digit characters where a-f is for lowercase letters and 0-9 is for digit between 0 to 9. 

[a-f0-9]{3} : This portion acts as the same as the above code, only it matches a sequence of 3 characters hence the 3 within the brackets towards the end.
  


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

Let us delve in and breakdown the components of our regex code
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

### Anchors

The anchors used here are the ^ and $ acting as the start and end of the line.

### Quantifiers

The {6} and {3} act as the quantifiers in the regex code. They indicate that the regex will match a sequence of 6 or 3 characters and digits.

### Grouping Constructs

([a-f0-9]{6}|[a-f0-9]{3}) the expression within the prantheses is a group. Meaning that the regex will match 6 or 3 characters

### Bracket Expressions

[a-f0-9] and [a-f0-9] indicate that the regex will match any characters of either lowercase letters or digits ranging from 0 - 9

### Character Classes

[a-f0-9] The bracket expressions in this code can also be considered as character class of sorts. The represent a class of characters including lower case letters a - f and digits from 0 - 9.

### The OR Operator

[a-f0-9]{6}|[a-f0-9]{3}  The | symbol that sits between the brackets allowing the exxpression to match the hex codes in both 3 and 6 character format.

### Flags

There are no flags involved with this regex.

### Character Escapes

There are no character escapes in this code.

## Author

Carlos Ogle
https://github.com/QotsaOmega266
