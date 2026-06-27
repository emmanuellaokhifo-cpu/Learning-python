# Learning-python 27th june 2026 - Booleans and conditionals

Conditional statements/ conditionals help control the flow of a programme based on conditiona hat are true or false.
Comparison operators are operators that let you compare two or more values, and return a boolean value.

<img width="1137" height="638" alt="image" src="https://github.com/user-attachments/assets/f328c161-b35a-4cb7-a0f8-d30d680cd682" />


These operators can be used in conditionals to compare values and run certain code based on whether the conditional evaluates to True or False.

In python the most basic conditional is if 
the body of the if statement contains a pass statement. When a pass statement is executed, nothing happens. This is a special keyword that can be used as a placeholder for future code and it is useful when empty code blocks are not allowed.

The code within the body of the if statement runs only when the condition evaluates to True

<img width="774" height="216" alt="image" src="https://github.com/user-attachments/assets/9e883b50-d5e9-4f5d-879c-acc290156d5e" />

in Python, code blocks are determined by indentation.
Blocks are also found in loops and functions, which you'll learn about in future lessons.
The else clause runs when the if condition is false. Here's the syntax for an if…else statement:

<img width="996" height="300" alt="image" src="https://github.com/user-attachments/assets/245e197e-bd0d-4c96-9c93-903ba42b8f79" />


Note that you cannot place any statements between the if block and the else clause. The following code would raise a SyntaxError:

<img width="698" height="331" alt="image" src="https://github.com/user-attachments/assets/78767af5-4b60-4b16-bdfc-31ce63b77416" />


There might be situations in which you want to account for multiple conditions. To do that, Python lets you extend your if statement with the elif (else if) keyword.

<img width="779" height="384" alt="image" src="https://github.com/user-attachments/assets/6dd2d75a-9569-4ead-9aa8-720df479447c" />
Note that you can use as many elif clauses as you want:

you will often run into situations where you need to compare multiple values at once. This can lead to nested conditional statements,

<img width="1099" height="371" alt="image" src="https://github.com/user-attachments/assets/eb748a12-50b0-47b7-9600-49a01a70c15e" />


In Python, every value has an inherent boolean value, or a built-in sense of whether it should be treated as True or False in a logical context. Many values are considered truthy, that is, they evaluate to True in a logical context. Others are falsy, meaning they evaluate to False.

<img width="1158" height="520" alt="image" src="https://github.com/user-attachments/assets/18c1bee8-20f5-49af-867a-56ca7ad7f794" />

<img width="697" height="341" alt="image" src="https://github.com/user-attachments/assets/a54fc906-1456-46a2-a57b-64eb9a50e485" />

There are three Boolean operators in Python: and, or, and not.

The and operator takes two operands and returns the first operand if it is falsy, otherwise, it returns the second operand. Both operands must be truthy for an expression to result in a truthy value.

The and operator is known as a short-circuit operator. Short-circuiting means Python checks values from left to right and stops as soon as it determines the final result.

You'll often use and within if statements to check if multiple conditions are met. Here’s how you can refactor the earlier example to use the and operator instead of nested if statements:

<img width="1049" height="336" alt="image" src="https://github.com/user-attachments/assets/c65accaa-9460-4a5f-b943-4d00fac7f149" />

Now let's take a look at the or operator. This operator returns the first operand if it is truthy, otherwise, it returns the second operand. An or expression results in a truthy value if at least one operand is truthy. The or operator is also known as a short-circuit operator. Here is an example:

<img width="1139" height="322" alt="image" src="https://github.com/user-attachments/assets/df318a41-1935-45f6-9889-04e61541d314" />

The last operator we will look at is the not operator which takes a single operand and inverts its boolean value. It converts truthy values to False and falsy values to True. Unlike the previous operators we looked at, not always returns True or False.

<img width="1061" height="294" alt="image" src="https://github.com/user-attachments/assets/3a98bd85-ae36-45eb-9a8a-cfbf07ac2a05" />

<img width="1153" height="311" alt="image" src="https://github.com/user-attachments/assets/ce6d1878-b825-464c-bc4d-7f8a1b760293" />
