# Regex-Code-Practise-
I explored the Regex library in Python, which comes built-in with the language.It works with text to extract key informations from longer passages. This library is quite useful in feature extraction and is used in NLP(Natural Language Processing).

A regex, Regular Expression, is a sequency of characters that forms a search pattern.

Re Module is used to work with Regular Expressions.
It can be imported using 

`import re`

## Overview of Python Regex Functions:

| Function | Description |
|----------|-------------|
| `findall` | This function scans through a string and returns a list of all the matches. It is incredibly useful for extracting all occurrences of a pattern without missing any, making it ideal for comprehensive data analysis tasks. |
| `search`  | The `search` function looks for the first location where the regex pattern produces a match and returns a Match object. This is particularly useful for testing if a pattern exists within a string and obtaining more detailed information about the match. |
| `split`   | This function uses a regex pattern as a delimiter to split the string at each matched pattern. The result is a list of substrings, which is useful for parsing and separating data into manageable parts. |
| `sub`     | The `sub` function replaces occurrences of the regex pattern in the string with a specified replacement string. It can be used to correct or update data by replacing outdated or incorrect terms efficiently. |
