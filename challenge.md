# Discover the Ternary Operator

In computer programming, **?:** is a ternary operator that is part of the syntax for a basic conditional expression in several programming languages. It is commonly referred to as the conditional operator, inline if (iif), or ternary if.
Ternary operators are mostly essential when setting a value to a variable depending on a condition.
**Example**
Let`s say that if a==42, i want variable b to be true, if a is not equal to 42, then the value of the variable b is false.
This is how that would look like:
```java
boolean b = (a==42)? true:false;
```

![Ternary Operator](http://4.bp.blogspot.com/-fRLKajLlCmU/VXMSKdoQgtI/AAAAAAAACaU/uY41sOxKmjs/s1600/ternary%2Boperator.PNG)

In Java this expression evaluates to:
> If foo is selected, assign selected foo to bar. If not, assign baz to bar.

**Example:**
```java
Object bar = foo.isSelected() ? foo : baz;
```

?[Check the options where result equals "foo"]
 - [ ] result = 2 > 4 ? "foo" : "bar"
 - [X] result = 2 < 4 ? "foo" : "bar"
 - [X] result = 2 > 4 ? "bar" : "foo"

Note that `Java`, in a manner similar to `C#`, only evaluates the used expression and will not evaluate the unused expression.

@[Complete the getNearestEnemy method using a ternary operator]({"stubs": ["Solution.java"], "command": "/bin/sh /project/target/run.sh"})

