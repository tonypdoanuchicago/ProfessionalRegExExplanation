# Northwestern University Challenge 17

This exercise is for Northwestern University Boot Camp's Challenge 17, which is to desscribe a fairly complex regular expression in detail.

Software applications normally has a user interface which will contain many fields. Some fields like username or password allow only valid input values.  However, programming for checking valid input can be tedious and may include much logic which is extra work and effort.  One common alternative to custom coding is leveraging regular expressions. Regular expressions cover many forms and possible inputs and can be used to check for valid email or even valid password.  These regular expressions are concise but powerful. However, regular expressions are cryptic in nature and can be hard to completely validate by visual inspection although there are tool that can be used to verify the validity of regular expressions.

## Summary

The table below breaks down the following Regular Expression.

See here an example of regular expression for the following:

^New Year.*\d{3}.*[!?][':;<>,.?\/].*Christmas$

## Table of Contents

- [See here the special characters for regular expressions. +.()*[]](#1)
- [See here a character set for regular expressions. [abc]](#2)
- [See here starting and ending anchors for regular expressions. ^$](#3)
- [See here special characters that represent entire character classes. \d+](#4)
- [See here character groupings for regular expressions.](#5)
- [^New Year](#A)
- [.*](#B)
- [\d{3}](#C)
- [.*](#D)
- [[!?]](#E)
- [[':;<>,.?\/]](#F)
- [.*](#G)
- [Christmas$](#H)

## Regex Components

### 1
+.()*[] are reserved characters.

### 2
[abc] is the character set with abc in it.

### 3
^$ are anchor characters for starting and ending points in the string.

### 4
 \d+ represents all number digits

### 5
(abc) groups sub parts of the regular expression.

### A
^New Year

Matches the beginning of the string followed by "New Year".

### B
.*

Matches any characters (zero or more) in between "New Year" and the next pattern.

### C
\d{3}

Matches any three digit number.

### D
.*

Matches any characters (zero or more) in between the three-digit number and the next pattern.

### E
[!?]

Matches either a question mark or an exclamation point.

### F
[':;<>,.?\/]

Matches any one of the specified characters.

### G
.*

Matches any characters (zero or more) in between the punctuation mark and the next pattern.

### H
Christmas$

Matches "Christmas" at the end of the string. The $ symbol denotes the end of the string.

## Author

Tony Doan is a software engineer with over 20 years of experience.  Contact him if you want to chat sometime.

https://github.com/tonypdoanuchicago
