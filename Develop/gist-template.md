# Northwestern University Challenge 17

This exercise is for Northwestern University Boot Camp's Challenge 17, which is to desscribe a fairly complex regular expression in detail.

## Summary

The table below breaks down the following Regular Expression.

^New Year.*\d{3}.*[!?][':;<>,.?\/].*Christmas$

## Table of Contents

- [^New Year](#A)
- [.*](#B)
- [\d{3}](#C)
- [.*](#D)
- [[!?]](#E)
- [[':;<>,.?\/]](#F)
- [.*](#G)
- [Christmas$](#H)

## Regex Components

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
