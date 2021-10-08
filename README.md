Java file = All of our code 

.md file = text, definition, ect; 

## Intro to Java
A Java program can be characterized as an **object** represented in a **class** 
Currently our program has a *Main* object. Inside of thsi object we have he main class. 

##Output 
In Java to put an item to the console we use: 'System.out.print()' and System.out.print1n()'
`System.out.println()` prints the  statement and move to the next line, while 
`System.out.print()` just prints the statement. 
## Comments 
A comment is used as user annotation with the purpose of being human readable. 

**Line Comments** follow double backslashes. `//` (Single Line Comment)

**Block Comments** are contained within `/* Comments */` (Multiple Lines Comment)

## Indentifiers 

In Java use the term **identifier** to describe a variable, parameter, constantm user-defined method or user-defined class. 

- Cannot begin with digit 
- Can only contain letters, digits and underscores 
age 
- Case-sensetive `age != Age` 

*Note:*
- class name starts with a capital latter 
- reserved words are entirely lowercase and may not be used as identifiers (Reserved words will show up in blue.)

## Types 
**Primitve** pr **built-in** types in Java are 
- `int` An interger 
- `boolean` True or False (booliean shirtColor = true) 
- `double` floating-point number (2.73) (compared to float in Python)
- `chair` single character 

*Note:* Integers have a fixed amount of memory, so there is a limit to how many digits you can store(2^31-1)

## Variables 
Veriables are a type of identifier that stores a value of a specific type 

we can create variables using **declatation** 
- `int age;` 
- `double x, y` 
- `boolean found;` 
- `char letter;` 

We can also intitlize a variable in its **declaration** 
- `int count = 1;` 
- `double p = 3.14;` 
- `char c = '8';` 

## Chars 
[ASCII CHART]
(https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit)

Each charactter is associated with an ASCII value. 


## Type cast 

One type can be cast to another compatible type if appropritate 

`chair letter = 'c';` 


int total, n; 
double average; 
average = (double)total/n; //total cast to doule ensure real division is used 

*Note:* Casting a floating-point number to an integer simply truncated the number (round down)

## Final Variables 
A *final variable* or *user-defind constant* indentified by the keyword `final`, is a quantity whose value will not change 

`final double TAX_RATE = 0.08;` 

- Constaint identifiers are, by convention, capitlized 
- `final` variable can be declared without initializing immdiately 