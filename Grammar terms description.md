# Legend for Grammar 
|Symbol|Meaning|
|---|---|
|\<ID\>|Variable name. Only digits, alphabets and underscore. Cannot start with digit|
|\<ARITHMETIC_EXPR\>|Arithmetic expression. Operands: real, float. Operators: +,-,/,\*|
|\<LINEAR_EXPR\>|Linear term expression. Expressions comprising arithmetic operands and - or + operators|
|\<FACTOR\>|Factor. Expressions comprising arithmetic operands and * or / operators|
|\<BOOLEAN_EXPR\>|Boolean expression. Operands: boolean. Operators: &&&, \|\|\||
|\<OR_EXPR\>|"Or" expression. Expressions comprising boolean operands and \|\|\| operand.|
|\<AND_EXPR\>|"And" expression. Expressions comprising boolean operands and &&& operand.|
|\<ARRAY_ELEMENT\>|Array element, which is int type.|
|\<VAR\>|Either a variable of int/ real type, or an array element.|
|\<LIST_INDICES\>|Space separated list of indices.|
|\<NUM\>|Any non-negative integer.|
|\<DECLARE_STMT\>|A single declare statement, of types SINGLELINE and MULTILINE|
|\<SINGLELINE_DECLARE_STMT\>|A single declare statement, used to declare all types except jagged array|
|\<MULTILINE_DECLARE_STMT\>|A multiline declare statement for declaring jagged arrays|
|\<IDS\>|A list of variable names separated by space.|
|\<STMTS\>|The non-terminal representing all the statements in the program.|
|\<DECLARE_STMTS\>|A bunch of declare statements.|
|\<ASSIGNMENT_STMTS\>|A bunch of assignment statments.|
|\<INDEX\>|Either a \<NUM\> or an \<ID\>|
|\<DIM\>|Dimension for a rectangular array|
|\<DIM2\>|Dimensions for a jagged array|
|\<ELEMS\>|One more more list of numbers separated by semicolons|
|\<LIST_NUM\>|A list of space separated numbers|
|\<R1_ARRAY\>||
|\<TYPE\>|Represents all the data types i.e. integer, real, boolean, rectangular and jagged arrays|
|\<ID_NUM\>|Either a variable name or a number|
|\<\>||
|\<\>||
|\<\>||
|\<\>||
|\<\>||
|\<\>||
