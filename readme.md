# Lexical Analyzer For Java
A lexical Analyzer for Java created using Python. The program takes a java file as input and scans the whole file. It categorizes each token of the program as one of the following:

- DELIMITER
- IDENTIFIER
- OPERATOR
- CONSTANTS
- KEYWORD
<br>

## Execution Steps:
1. Copy jLex.py to your project folder

2. Do this in your file
```python
from jLex import LexicalAnayzer

x = LexicalAnalyzer("./input.java") #Takes file path as Input
x.generateLexicalTable() 

''' Ouputs following data to 'lexTable.txt'
+--------+----------+------------+---------------+
|  Line  |  Lexeme  |   Token    |  Token Value  |
+--------+----------+------------+---------------+
|   1    | public   | KEYWORD    |    (KW,24)    |
|   1    | class    | KEYWORD    |    (KW,41)    |
|   1    | input    | IDENTIFIER |    (ID,01)    |
|   1    | {        | DELIMITER  |    (DL,03)    |
|   2    | public   | KEYWORD    |    (KW,24)    |
|   2    | static   | KEYWORD    |    (KW,39)    |
|   2    | void     | KEYWORD    |    (KW,40)    |
|   2    | main     | IDENTIFIER |    (ID,02)    |
|   2    | (        | DELIMITER  |    (DL,01)    |
|   2    | String   | IDENTIFIER |    (ID,03)    |
|   2    | args     | IDENTIFIER |    (ID,04)    |
|   2    | [        | DELIMITER  |    (DL,10)    |
|   2    | ]        | DELIMITER  |    (DL,11)    |
|   2    | )        | DELIMITER  |    (DL,02)    |
|   2    | {        | DELIMITER  |    (DL,03)    |
	.		.			.
	.		.			.
	.		.			.
'''
*/
```

### Developer:
- <a href="https://github.com/yashoswalyo">@yashoswalyo </a>
