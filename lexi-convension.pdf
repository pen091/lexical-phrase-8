Here's a clear definition of each of the 8 lexical conventions in C, as used by the compiler during the preprocessing and compilation phases:


---

✅ 1. Physical Source File

The actual .c or .h file written by the programmer.

It contains the program text in the form of characters (using the source character set).

This is the starting point for lexical analysis and preprocessing.



---

✅ 2. Trigraph Sequences

A trigraph is a sequence of 3 characters starting with ?? used to represent characters that might be missing on some keyboards.

They are replaced before any other processing.


Trigraph	Replaced With

??=	#
??(	[
??)	]
??!	`
??/	\
??'	^
??<	{
??>	}
??-	~


> Example: ??=define becomes #define




---

✅ 3. Line Splicing (\ at end of line)

A backslash (\) at the end of a line joins it with the next line.

The backslash and newline are replaced with nothing.

Used to split long lines for readability.


> Example:



#define MESSAGE "This is a \
continued string"


---

✅ 4. Preprocessing Directives

Commands starting with # that instruct the preprocessor to do something before actual compilation.

Examples:

#include <stdio.h>

#define PI 3.14

#ifdef DEBUG


These are not tokens themselves and are handled before the compiler parses C code.



---

✅ 5. Tokens

The basic building blocks of a C program.

C source code is broken down into tokens during lexical analysis.


Types of tokens:

Keywords: int, return, if, else, etc.

Identifiers: names like main, x, count, etc.

Constants: numeric values like 42, 3.14, 'A'

String literals: like "Hello World"

Operators: +, -, =, ==, &&, etc.

Punctuation/Symbols: {, }, (, ), ,, ;, etc.



---

✅ 6. Whitespace

Includes space, tab, newline, and form feed characters.

Used to separate tokens where necessary.

Ignored otherwise (e.g., multiple spaces between tokens are collapsed).


> Example:



int     main ( ) { return 0 ; }

is equivalent to:

int main() { return 0; }


---

✅ 7. Comments

Used to annotate code. Removed by the preprocessor before tokenization.


Two types:

1. Block comments:

/* This is a comment */


2. Line comments (since C99):

// This is a comment



> Comments cannot be nested in standard C.




---

✅ 8. Character Set (Source Character Set)

Defines the set of characters available in the source code.

Must include:

Letters (A-Z, a-z)

Digits (0-9)

Special characters (+ - * / = < > ( ) { } [ ] ; , . # " ' \ etc.)

Whitespace characters



> These characters are used to form tokens, literals, and identifiers.




---

🔎 Summary Table

#	Lexical Convention	Description

1	Physical source file	The raw .c or .h file
2	Trigraph sequences	3-char replacements like ??= → #
3	Line splicing (\)	Joins two lines into one
4	Preprocessing directives	#include, #define, etc.
5	Tokens	Keywords, identifiers, literals, operators
6	Whitespace	Space, tabs, newlines (used for separation)
7	Comments	/* */ and //, removed before compiling
8	Character set	Basic characters used to build code



---

Let me know if you'd like this in PDF, cheatsheet, or visual format.



