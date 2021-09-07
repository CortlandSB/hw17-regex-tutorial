# Regular Expression Tutorial

A regular expression is a pattern of characters that helps to match text.

## Summary

The regex I will be describing is a regex matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`.

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

### Anchors
The snippit `/^#` is an anchor. The anchor says something regarding the string based on the character next to it. The `^` character signifies the beginning of a string. The `#` character signifies a hexadecimal number.
### Quantifiers
The snippit `?` is a quantifier signifying a boolean value. The quantifier `[a-f0-9]{6}` signifies how many times the preceeding section matches. The `{6}` here means there are six occurances of the string in the preceeding bracket expression. The `{3}` in `[a-f0-9]{3}` signifies there are three instances of the string in the preceeding bracket expression.
### Grouping Constructs
The `()` encompassing `([a-f0-9]{6}|[a-f0-9]{3})` groups the characters as a regular expression, treating the characters as a single unit.
### Bracket Expressions
The `[]` around `[a-f0-9]` is a bracket expression that matches a character pattern within the brackets. In this case, the string must have at least one character between a and f, and between 0 and 9.
### Character Classes
The `a-f0-9` is a charcter class, something that matches only one character in the set of characters.
### The OR Operator
The `|` in the middle of `[a-f0-9]{6}|[a-f0-9]{3}` is an OR Operator. This is a boolean matching the expression either before or after the symbol. This signifies a match with a string containing either three or six characters.

## Author

My name is Cortland Styles-Brown
