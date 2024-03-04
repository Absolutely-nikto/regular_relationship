# regular_relationship

Regular expressions are powerful tools used in computer science and programming to search, match, and manipulate text based on specific patterns. They are commonly used in tasks like data validation, text parsing, and search and replace operations. In this article, we will explore several examples of regular expressions along with explanations.

1. ([a-fA-F0-9]{1,4}:)){7}[a-fA-F0-9]{1,4}|(/\d{1,3})
This regular expression matches IPv6 addresses or file paths. The first part ([a-fA-F0-9]{1,4}:)){7}[a-fA-F0-9]{1,4} matches an IPv6 address in the format of 8 groups of hexadecimal digits separated by colons. The second part (/\d{1,3}) matches a file path starting with a forward slash followed by 1 to 3 digits.

2. [А-Я][а-я]+\s[А-Я][а-я]+\s[А-Я][а-я]+\s[А-Я]{1,3}|[А-Я][а-я]+\s[А-Я][а-я]+\s[А-Я][а-я]+\s[А-Я]{1,3}\s\d{1,5}
This regular expression matches Russian names followed by a middle name and surname, optionally followed by a patronymic name and a numerical value. It is designed to validate Russian full names with different variations.

3. [А-ЯЁ,а-яё]{5}(-)([0-9]|[1-9][0-7]?[0-9]|800)(/)[АЯ-Ё]{1,4}
This regular expression matches a specific pattern consisting of 5 Cyrillic characters, a hyphen, a number between 0 and 800, a forward slash, and 1 to 4 Cyrillic characters.

4. [АВЕКМНОРСТУХ]\d{3}[АВЕКМНОРСТУХ]{2}(102|02|702)
This regular expression matches Russian vehicle registration numbers by specifying the format of a letter followed by three digits, two letters, and one of the specified ending numbers (102, 02, or 702).

5. [0-9A-Fa-f]{32}
This regular expression matches a 32-character hexadecimal string commonly used in tasks like verifying checksums or cryptographic hashes.

6. [A-CG-Z]{3}-(000[1-9]|00[1-9]\d|0[1-9]\d\d|[1-3]\d\d\d|4[0-25-9]\d\d|44[6-9]\d|445[1-9]|5000)\+([А-ЯЁ]{3}-\d{3}|[A-Z]{3}/\d{2})
This regular expression matches a specific pattern consisting of three letters followed by a hyphen and a range of numerical values, then a plus sign and another pattern of three Cyrillic letters followed by three digits or three Latin letters followed by two digits.

7. ВУС №\d{6}[А-Д]
This regular expression matches a specific format for a code starting with "ВУС №" followed by six digits and ending with a letter from A to D.

Regular expressions are versatile tools that can be customized to match specific patterns in text data. Understanding how to use them effectively can greatly enhance text processing tasks in various programming languages.
