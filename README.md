# Read-05---Operators-and-Loops

# Expressions and operators
- describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.

# Operators
- JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

1- Assignment operators

2- Comparison operators

3- Arithmetic operators

4- Bitwise operators

5- Logical operators

6- String operators

7- Conditional (ternary) operator

8- Comma operator

9- Unary operators

10 Relational operators

- javaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

# operand1 operator operand2
For example, 3+4 or x*y.


A unary operator requires a single operand, either before or after the operator:

# operator operand

# Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.



# Compound assignment operators
Name	                                           Shorthand operator	             Meaning

Assignment	                                     x = y	                         x = y

Addition assignment                            	x += y	                       x = x + y

Subtraction assignment	                        x -= y	                       x = x - y

Multiplication assignment                     	x *= y	                       x = x * y

Division assignment                          	x /= y	                        x = x / y

Remainder assignment	                       x %= y                          	x = x % y

Exponentiation assignment                  	x **= y                         	x = x ** y




# Comparison operators
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

-[x] var var1 = 3;

-[x]  var var2 = 4;



# Logical operators
Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators


# Logical operators
Operator	Usage	Description
Logical AND (&&)	expr1 && expr2    Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.

Logical OR (||)	expr1 || expr2	Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false.

Logical NOT (!)	!expr	Returns false if its single operand that can be converted to true; otherwise, returns true.

	:grinning:

