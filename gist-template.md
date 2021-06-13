# Regrex Totorial: Email 

A regular expression is a sequence of characters that forms a search pattern. The user can define what needs to be searched in a text with the assistance of regular expressions. Regular expressions can be characters from the alphabet, numerical digits, or special characters. 

## Summary

The regex code we will review is: ^\w+([.-]?\w+)*@\w+([.-]?\w+)*(\.\w{2,3})+$


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
^\w+([.-]?\w+)*@\w+([.-]?\w+)*(\.\w{2,3})+$

### Anchors
The position anchors ^ and $ match the beginning and the ending of the input string.

### Quantifiers
for this example + is used to elaberate another sequesnce to match as a greedy quantifier. we use {2,3} as well to specify the input should be a minnimun of 2 charactors to a maximum of 6 characters. 

### Grouping Constructs
\w matches any word character (equivalent to [a-zA-Z0-9_])

n-capturing group (?:\.[\w-])* matches the previous token between zero and unlimited times, as many times as possible, giving back as needed

### Bracket Expressions
[.-]? is used to matche an optional dot or hyphen.

### Character Classes
The charactor class \w is used to classify any letter, digit, or underscore 

### The OR Operator
the OR operator (|), the expression [abc] could be written as (a|b|c).
No or operator for this example 

### Flags
m modifier: multi line. Causes ^ and $ to match the begin/end of each line not only begin/end of string.

g modifier: global. All matches, but don't return after first match

### Character Escapes
 The backslash (\) in a regex escapes a character that otherwise would be interpreted literally.
 
 all special characters, including the backslash (\), lose their special significance inside bracket expressions.

## Author

Name: Michael Birdsong 

Github Repository Link: https://github.com/mikebird2414