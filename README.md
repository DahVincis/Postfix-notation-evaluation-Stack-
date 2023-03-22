# Postfix-notation-evaluation-Stack-
Project for Data Structures in Python course.

This is what needed to be done for the project

Project 4: Stack
Project 4 is to create a program to evaluate a postfix notation using a stack. You
must use a Stack class to implement this Abstract Data Type.
Given a postfix notation: 3 5 1 - * 2 +
Process each term / token in the expression (operand or operator) one by one.
If a token is an operand, push it into the stack.
If a token is an operator, pop the stack top item as the 2nd operand and pop the next
item as the 1st operand. Evaluate the expression and push the result back into the
stack. This result will be either the operand for the next operation or, if that was the
last operation, the result of the entire postfix notation.

For a valid postfix notation, when you are done processing the expression, there
should be exactly one token on the stack, which is the answer to your expression.
If you program is attempting to pop an empty stack, or if your expression evaluation
ends with more than one token in the stack, the postfix notation is invalid.
Your program should be able to take any postfix notation as input and evaluate to
give the result. It should also be able to determine if an expression is valid or
invalid.
