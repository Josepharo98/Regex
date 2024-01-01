# Title (A tutorial on Hex Value)

## Summary

Hello, in this tutorial, I will be breaking down the code `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` and what it does when you include it in Regex. Regex is a sequence of characters that describe a search pattern. There can be a pattern for URL's, HTML Tag's, Email's, and more. This specific code goes over matching the Hex Value. Let's begin!!

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
The Achors in this code start with [^]
and ends with [$]
 This shows were the start and the end of the code is. It indicates that the matching pattern should start at the beginning of the input string and the end of the of the input string.
### Quantifiers
The quantifiers in this code is [?]

Quantifiers in regular expressions are symbols or characters that show the amount or repetition of the characters or groups. In this case, this would show for 0 or 1 appearances.

### Grouping Constructs
The [()] is used for grouping and applying the quantifiers to everything within the [()]

### Bracket Expressions
The bracket expressions within this code is [ [a-f0-9] ]. The point of this is to match any single character within the specified range. So a through f and zero to 9

### Character Classes
The Character Classes within this code is the second [ [a-f0-9] ]. This matches any single character that is a lowercase hexadecimal digit. This is basically the same as the bracket expression.

### The OR Operator
The [|] in the code represents the Operator. This separates two alternatives within an expression. An example of this is cat|dog. Both fall under animal but it may change based on input

### Flags
There are none in this code but a flag can be a grouping of some sort. If you didnt want there to be a difference between capitals and lowercase, you would use a flag to ignore the two. It would look like this [pattern/i]

### Character Escapes
There are none in this code but character escapes often uses specific character to represent a action or meaning. For example, \d is a shorthand for matching any digit (equivalent to [0-9]). These are shortcut that you can use within your code
## Author

My name is Joseph Aro and the link to my github is https://github.com/Josepharo98/Regex
