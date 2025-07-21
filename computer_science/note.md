## Introduction to Computer Science and Programming Using Python


`For these problems, it's important to understand the priority of Boolean operations. The order of operations is as follows:

Parentheses. Before operating on anything else, Python must evaluate all parentheticals starting at the innermost level.

not statements.

and statements.

or statements.

What this means is that an expression like

not True and False
evaluates to False, because the not is evaluated first (not True is False), then the and is evaluated, yielding False and False which is False.

However the expression

not (True and False)
evaluates to True, because the expression inside the parentheses must be evaluated first - True and False is False. Next the not can be evaluated, yielding not False which is True.

Overall, you should always use parenthesis when writing expressions to make it clear what order you wish to have Python evaluate your expression. As we've seen here, not (True and False) is different from (not True) and False - but it's easy to see how Python will evaluate it when you use parentheses. A statement like not True and False can bring confusion!`

* 
