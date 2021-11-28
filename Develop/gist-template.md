# Hex value Regex tutorial

This tutorial is going to explain the use of regex to match hex values using the expression /^#[0-9A-F]+$/

## Summary

What is Regex?
A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern.
When included in code or search algorithms, regular expressions can be used to find certain patterns of characters
within a string, or to find and replace a character or sequence of characters within a string. They are also frequently
used to validate input.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

- ^ – The caret anchor matches the beginning of the text.
- $ – The dollar anchor matches the end of the text.

### Quantifiers

The "+" determines that there should be at least one matches one or more occurrences of the one-character
regular expression

### Bracket Expressions

Bracket expressions for hex value validation includes the character sets of [0-9A-F], which is matching any letter
a-z and is case senstive. It also matches a character 0-9

### Greedy and Lazy Match

This regrex includes greedy matches. Since it includes the "+" Quantifier, it will match as many times as possible
giving back as needed

## Author

[Github](https://github.com/luismrosales)
