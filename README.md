# Matching Email - Regex Tutorial

Regex tuorial will explain how to match an email using the expression `^([a-z\d][a-z\d_\-.]+[a-z\d]){1,10}@[a-z\d-]{2,20}\.[a-z]{2,10}.(\.[a-z]{2,20})?$`. This Regex expression is a unique text string for describing a particular pattern and how it checks for a valid email address.

## Summary

Regular expression refers to encoded text string designed to match pattersn in other strings. Regular expressions are<br> 
particularly helpful when you need to find a string of characters that matches the format of any email address.<br> 
This process is commonly used for identifying whether a user has entered an email correctly.

## Table of Contents

- [Anchors](#anchors)
- [Meta Sequences](#meta-sequences)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

Anchors have a speacial meaing regular expressions. They do not match any character. Instead,<br> 
they match a position before and after characters.

* `[^]` - The caret achor matches the beginning of the text.<br>
* `[$]` - The dollar anchor matches the end of the text.<br>
                                                                      
### Meta Sequences

Meta sequences-characters are the foundation of regular expressions. Characters in Regex are understood to be either a<br>
metacharacter with a special meaning or a regular character with a literal meaning.

* `[\d]` - Matches any decimakl digit. Equivalent to `[0-9]`.<br>
* `[\]`  - Converts metacharacters to literal characters, and also allows literal matching of the regex delimiter in use.<br>
* `[.]`  - Matches any character other than newline (or including line terminators with /s flag).<br>
* `[?]`  - Question mark matches when the character preceding `?` 0 or 1 time only making the character match optional.

### Bracket Expressions

Bracket expressions are a list of charactwers and/or character classes enclosed in brackets []. Use bracket expressions<br> 
to match single characters in a list, or range of character in a list 

* `[a-z\d]` 

### Character Classes

Character classes distinguish kinds od characters such as, for example, distinguishing between letters and didgits.

* `[a-z]` - Matches any characters between a and z, including a and z.

### Alphanumeric characters

Alphanumeric, also referred to as alphanumeric, is a term that encompasses all of the letters and numerals in a given<br>
language set.

* `{1,10}` - This alphanumeric character allow a minimum of 3 and a maximum of 30 characters for the username of the email.
* `[_]`    - The `[_]` character in a regular expression that immediately follows the alphanumeric string.

## Author

I'm a student at UCLA Extension. To view view my projects please go to https://github.com/toddrgarner.

## Github Gist Link

https://gist.github.com/toddrgarner/6c2f42d7bf6653ff7dcf8f5b88f9d0a6

## Github Repository

https://github.com/toddrgarner/regex-tutorial

© 2022 Todd Garner. Confidential and Proprietary. All Rights Reserved.