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

### Bracket Expressions

### Character Classes

### The OR Operator
The `|` in the middle of `[a-f0-9]{6}|[a-f0-9]{3}` is an OR Operator. This is a boolean matching the expression either before or after the symbol. This signifies a match with a string containing either three or six characters.
### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
