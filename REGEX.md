# Regex Cheatsheet

<details>
<summary>Anchors</summary><br>
  
| Character  | Description |
|---|---|
| `^` |  Start of string, or start of line in multi-line pattern |
| `\A`| Start of string |
| `$` | End of string, or end of line in multi-line pattern |
| `\Z`| End of string |
| `\b`| Word boundary |
| `\B`| Not word boundary |
| `\<`| Start of word |
| `\>`| End of word |

</details>


<details>
<summary>Character Classes</summary><br>

| Character  | Description  |
|---|---|
| `\c`  | Control character  |
| `\s` | White space |
| `\S` | Not white space |
| `\d` | Digit |
| `\D` | Not digit |
| `\w` | Word |
| `\W` | Not word |
| `\x` | Hexadecimal digit |
| `\O` | Octal digit |

</details>


<details>
<summary>POSIX</summary><br>

| Character  | Description  |
|---|---|
| `[:upper:]` | Upper case letters |
| `[:lower:]` | Lower case letters |
| `[:alpha:]` | All letters |
| `[:alnum:]` | Digits and letters |
| `[:digit:]` | Digits |
| `[:xdigit:]` | Hexadecimal digits |
| `[:punct:]` | Punctuation |
| `[:blank:]` | Space and tab |
| `[:space:]` | Blank characters |
| `[:cntrl:]` | Control characters |
| `[:graph:]` | Printed characters |
| `[:print:]` | Printed characters and spaces |
| `[:word:]` | Digits, letters and underscore |

</details>


<details>
<summary>Assertions</summary><br>

| Characters  | Description  |
|---|---|
| `?=` | Lookahead assertion | 
| `?!` | Negative lookahead |
| `?<=` | Lookbehind assertion |
| `?!=` or `?<!` | Negative lookbehind | 
| `?>` | Once-only Subexpression | 
| `?()` | Condition [if then] | 
| `?()`| Condition [if then else] |
| `?#` | Comment|

</details>


<details>
<summary>Quantifiers</summary><br>

| Character  | Description  |
|---|---|
| `*` | 0 or more |
| `{3}` | Exactly 3 |
| `+` | 1 or more |
| `{3,}` | 3 or more |
| `?` | 0 or 1 |
| `{3,5}` | 3, 4 or 5 | 

```
Note: Add a ? to a quantifier to make it ungreedy.
```
</details>
