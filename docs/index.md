###

 \\\
 Bita Massoudi
 11/28/2022
 Foundations of Databses and SQL Programming
 Assignment07
 bitamass/DBFoundations-Module07 (github.com)
 \\\

**Introduction:** 
A user-defined function (UDF) in SQL Server is a programming construct that accepts parameters, uses these parameteres and returns a type of result. 

**When to use a SQL UDF:**
SQL UDF can provide certain advantages. One such advantage is that the same logic does not need to be written multiple times. Within the database, the function can be written once and be called multiple times. It also reduces the compilation time of queries by catching the execution plan and resusing it.  Additionally, it reduces the network traffice because of its cache plan.

**Differences between Scalar, Inline, and Multi-Statement Functions:**
Scalar Functions: A scalar function accepts any number of parameters and returns one value. The term scalar differentiates a single, "flat" value from more complex structured values, such as arrays or result sets.  This pattern is much like that of traditional functions written in common programming language.

Inline Table-Valued Functions: Similar to a view, this type of function returns a result set. However, unlike a view, functions can accept parameters. The inline function's syntax is simple. In the function definition, the return type is set to a table. A return statement is used with a select query in parenthesis.

Multi-Statement Table-Valued Functions: Multi-Statement functions can be used to do some unique things outside the context of a standard SELECT statement. This type of function returns a table-type result set, but the table is explicitly constructed in script. This can be used to accomplish one of two things: either to process some very unique logic by assembling a virtual table, or to duplicate the functionality of an inline function in a more verbose and compiled way. 

**Conclusion:**
UDFs in SQL Server programming are constructs that can accept parameters. Scalar function, Inline table-valued functions and Multi-Statement table-valued functions are all User defined functions.



