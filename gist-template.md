# Title (replace with your title)

In this article we will be explaining Regex vaildation for matching an email utilizing the following code: 
`^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$`

## Summary

 Regex expression, which is short for regular expression, is that, at the beginning of the string (`^`), inclue group (`()`) in sets (`[]`): a-z, 0-9, _, ., and -. It also write the dot as (`\.`). In (`()`), accept characters from (`[]`) characters `a-z` and character ".", repeated between 2-6 times `{2,6}` followed by the end of the string `$`.


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
There are two characters used for anchors, ^ and $. 
The ^ anchor requires that the characters or string of characters that follow it must match, while the $ anchor requires that the characters or string infront of it must match.
Regex is case sensitive so for example, (^How) and (How are you) match but (how) does not match. 

### Quantifiers
Quantifiers {} take in parameters for how many characters you are looking for. 
If {4} then it means {} will be looked 4 times. If {5,} then it means {} will be taken at least 5 times. If {2,6} then it will look 2 to 6 times.

### Grouping Constructs
  Grouping Constructs are divided into two different categories which are capturing and non-capturing. Capturing group is used to match character sequence.

### Bracket Expressions
Characters in brackets [] shows the range we want to match. They are also known as positive character group. 

### Character Classes
 Character Classes brings meaning to set of characters. 

. means match any character except (\n) which means new line

    `\d` is one character class present in the email regex. \d means match any Arabic numeral [0-9].

### The OR Operator
    (|) is the OR Operator, which can be used to say [ab] = (a|b).

### Flags
Flags define additional functionality or limits for regex, which can be placed at the end of regex. 


### Character Escapes
    (\) is an Escape Character. If (\) is in front of a character, then it makes it have no meaning to it. 

## Author

My Repo: http://github.com/JulianKM
