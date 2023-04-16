# Regex Tutorial: Matching an Email

Have you ever heard of regular expressions or "regex" for short? They're a way to find specific patterns in a piece of text. Matching an email address using regex is one of the most common uses of this tool. An email address has a specific format, with a username, the "@" symbol, and a domain name. By using a specific regex code, we can find and check if an email address is valid or not. We'll show you how to do it with some easy examples! [Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`]

## Summary

Matching an email using Regex means finding a specific pattern of characters that follows a certain format, like the format of an email address.  [Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`] A typical email address has a username, the "@" symbol, and a domain name. By using a specific set of rules called a Regex code, we can extract or check if an email address is valid or not. This is helpful for tasks like processing data and checking for errors.

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
To match an email using regex, we need to define a specific pattern that matches the format of an email address. Here are the components of a regex code for matching an email:

The "@" symbol: This is a required component of an email address, so our regex code needs to include the "@" symbol in the pattern.

The username: This is the part of the email address that comes before the "@" symbol. It can include letters, numbers, and some special characters like dots and underscores. We can use regex to define the pattern for the username.

The domain name: This is the part of the email address that comes after the "@" symbol. It includes the name of the email provider and the top-level domain (such as ".com" or ".edu"). We can use regex to define the pattern for the domain name.

By defining these components in a regex code, we can search for and extract email addresses from text sources. We can also use regex to validate if an email address is in the correct format.

### Anchors
Anchors belong to the family of regex tokens that don't match any characters, but that assert somethin about the string or the matching process. They do not match any character. Instead, they match a position before or after characters. When trying to use regex to match an email address, the regex expression for matching an email are ^, which indicates the beginning of the string and $ to indicate the ending of the string.

### Quantifiers
Quantifiers indicate numbers of characters or expressions to match. Quantifiers specific to matiching an email are the + operator, which will connectthe user's email name, the email service, and the domain. Also, {2,6} is a quantifier the will allow a match range of 2 to 6 characters for the character set of [a-z\.].

### Grouping Constructs
Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string. First, ([a-z0-9_\. -]+) will capture the email name. Second, ([\da-z\. -]+) will capture the users email provider. Third, { 2,6} will capture the domain.

### Bracket Expressions
Bracket Expressions are referencing the characters that are wrapped in the []. For instance, [a-z0-9_\.-] will match any letter a-z, any number 0-9, and the characters _, ., and -.

### Character Classes
The regex for matching an email contains only one character class which is \d. This allows us to match a single character that is a digit from 0-9.

### Character Escapes
The regex for matching an email does contain character escapes. The \. is used will it literal instead of a special character.

## Author

I hope to improve everyday, and one day to become great at writing code! My [Github Page Address](https://github.com/)
