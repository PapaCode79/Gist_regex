# My Regex Password_generator.md
Password-Generator.md

## Description
A Regular Expressions allows us to check a series of characters for "matches". To make sure it confirms some kind of patterns to describe for matches we created.

## Flags

The global search flag makes the RegExp search for a pattern throughout the string, creating an array of all occurrences it can find matching the given pattern. It allow you to control the regex engine.


## Groups

Capturing groups are a way to treat multiple characters as a single unit. They are created by placing the characters to be grouped inside a set of parentheses. For example, the regular expression (cat) creates a single group containing the letters "c" "a" and "t".


# Title (Password_Generator.md)

Regular Expression checks for validation for string of characters. Such a email, phone numbers, password etc. 


## Summary

My Password_generator.md is a Regular Express that allows us to check a form field to try and match a valid secured password using all the requirements for matches. It must be minimum eight characters, at least one uppercase letter, one lowercase letter and one number. 
My code is "^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d]{8,}$"


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

Anchors are regex tokens that don't match any characters but that say or assert something about the string or the matching process. Anchors inform us that the engine's current position in the string matches a determined location: for example, the beginning of the string/line, or the end of a string/line.
They do not match any character. Instead, they match a position before or after characters.

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.
Quantifiers are used to quantify how many times a part of your regular expression should be repeated.

### OR Operator

Regular expressions are combinations of special character operators, which are symbols that control the search, that you can use to construct search strings for advanced find and/or replace searches.

### Character Classes

In the context of regular expressions, a character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string.
Character classes are one of the most commonly used features of regular expressions. You can find a word, even if it is misspelled, such as sep[ae]r.


### Flags

The global search flag makes the RegExp search for a pattern throughout the string, creating an array of all occurrences it can find matching the given pattern. It allow you to control the regex engine.

### Grouping and Capturing

Capturing groups are a way to treat multiple characters as a single unit. They are created by placing the characters to be grouped inside a set of parentheses. For example, the regular expression (cat) creates a single group containing the letters "c" "a" and "t".

### Bracket Expressions

A bracket expression is either a matching list expression or a non-matching list expression. It consists of one or more expressions. Examples: ordinary characters, collating elements, collating symbols, equivalence classes, character classes, or range expressions. It indicate a set of characters to match. Any individual character between the brackets will match, and you can also use a hyphen to define a set.

### Greedy and Lazy Match

Greedy means your expression will match as large a group as possible, lazy means it will match the smallest group possible. 
The lazy mode of quantifiers is an opposite to the greedy mode. It mean repeat minimal number of times. Whereas, greedy quantifiers will match their preceding elements as much as possible.

### Boundaries

A word boundary is a zero-width test between two characters. 
A word boundary, in most regex dialects, is a position between \w and \W (non-word char), or at the beginning or end of a string if it begins or ends (respectively) with a word character ( [0-9A-Za-z_] ). So, in the string "-12" , it would match before the 1 or after the 2.

### Back-references

Back-references are regular expression commands which refer to a previous part of the matched regular expression. Back-references are specified with backslash and a single digit (e.g. ' \1 '). The part of the regular expression they refer to is called a subexpression, and is designated with parentheses.

### Look-ahead and Look-behind

 Lookahead and lookbehind (commonly referred to as “lookaround”) are useful when we'd like to match something depending on the context before/.
The lookbehind asserts that what immediately precedes the current position is a lowercase letter. And the lookahead asserts that what immediately follows the current position is an uppercase letter.

## Author

A short section about the author with a link to my GitHub profile.
Salut! I am Badara Dia, a professional and aspiring Front-End and Back-End Web Developer. I am a George Washington Bootcamp Spring 2022 graduate for Full-stack Development.
