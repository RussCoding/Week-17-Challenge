# Regex Tutorial on Expression for Email

Regex is short for regular expression, and is a grouping of characters that define a certain pattern or set of constraints.

## Summary

Emails are an extremely important form of communication in the modern digital space.  Email's are a  reliable way to to get messages across in a protected way.  Email's have a very rigid structure and every email follows a certain pattern for how they are written.  The regex expression which could be used to represent emails is:  
/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors represent the beginning and end of a string.  They are important to determine the boundaries of a regex expression. In the expression for email ^ represents the begginging of the expression and $ represents the end.
### Quantifiers
Quantifiers are a range of numbers placed between two curly brackets {} and that range represents the minimum and maximum limits for a section of the string.  The {2,6} on the left of the dollar sign shows that the string to the left of it has to be between 2-6 characters long.
### OR Operator
The OR operator is represented by: |.  The email regex expression does not contain an OR operator.
### Character Classes
In regex character classes show a set of characters inbetween square brackets[] and they show what type of characters can be in a certain section. In [\da-z.-] the \d represents any digit from 0-9 and a-z represents any lowercase character.
### Flags
Flags are at the end of a regex expression and represent additional functionalities.  
### Grouping and Capturing
Parenthesis are used for grouping and represent different sections of substring.  In email there are 3 groups ([a-z0-9_.-]+),  ([\da-z.-]+), ([a-z.]{2,6}) which represent 3 differnt section the email username, the name of the email company such as gmail, and then the .com/.net, etc.
### Bracket Expressions
Bracket expressions are used for showing the range of characters which can be in that section.  [0-9] would be only numbers, [a-z] would be lowercase letters, etc.
[a-z0-9_.-] would be lowercase, numbers, and underscore, perios, hyphens.  
[\da-z\.-] is the same but no underscore.
[a-z\.] is lowercase letters and periods.
### Greedy and Lazy Match
? is a lazy match and + is a greedy match.  There are no lazy matches for email.  
### Boundaries
Boundaries make assertions about what can be mathed to the left and right of the current position.  This example does not have boundaries.
### Back-references
Back references are used to match the same text in the previous group and are used to make the expression shorter.  There are none in this example
### Look-ahead and Look-behind
Allows a match only if its followed or preceded by a certain pattern.  There are none in this example.
## Author

My name is Russel and this was an interesting and also the last assignment for me to complete for this course

Github Repository: https://github.com/RussCoding
