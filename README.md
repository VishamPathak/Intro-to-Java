Java file = All of our code

.md file = All of our notes

## Intro to Java

A Java program can be characterized as an **object** represented in a **class**.
Currently our program has a *__Main__* object. Inside of this object we have the *__Main__* class.

## Output
In Java to output an item to the console we use: 'System.out.print()' and 'System.out.println()'
`System.out.println()` prints the statement and moves to the next line, while 
`System.out.print()` just prints the statement.

## Comments

A comment is used as user annotation with the purpose of being human readable.

**Line Comments** follow double backslashes. `//` (Single Line Comment)

**Block Comments** are contained within `/* Comments */` (Multiple Lines Comment)

## Identifiers

In Java use the term **Identifier** to describe a variable, parameter, constant, user-defined method or user-defined class.

- Cannot begin with digits
- Can only contain letters, digits, and underscores age
- Case-sensitive `age != age`

*Note: *
- class names starts with a capital letter
- reserved words are entirely lowercased and may not be used as identifiers (Reserved words will show up in blue.)

## Types
**Primitive** or **built-in** types in Java are
- `int` An integer
- `boolean` True or False (boolean shirtColor = true)
- `double` Floating-point number (2.73) (compared to floats in Python)
- `char` Single character

*Note* Integers have a fixed amount of memory, so there is a limit to how many digits you can store (2^31 - 1)

## Variables
Variables are a type of identifier that stores a value of a specific type

we can create a variable using **declaration**
- `int age;`
- `double x, y`
- `boolean found;`
- `char letter;`

We can also initialize a variable in its **declaration**
- `int count = 1;`
- `double p = 3.14;`
- `char c = 8;`

## Chars
[ASCII CHART]
(https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit)

Each character is associated with an ASCII value.


## Type cast 

One type can be cast to another compatible type if appropriate

`char letter = 'c';`
```

in total, n;
double average;
average = (double)total/n //total cast to double to ensure real division is used
```

*Note :* Casting a floating-point number to an integer simply truncates the number (rounds down)

## Final Variables
A *final variable) or *user-defined constant*, identified by the keyword `final`, is a quantity whose value will not change

`final double TAX_RATE = 0.08;`

- Constant identifiers, are, by convention, capitalized
- `final` variable can be declared without initializing immediately


