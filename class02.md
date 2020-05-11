# class02

> this is my notes from readings we do in **_201 course_** in my advance coding scholarship 

Here is a list of things a learnt in this reading: 

# Html book:

## Chapter 2: “Text”
- [x] HTML elements are used to describe the structure of the page (e.g. headings, subheadings, 
    paragraphs).
- [x] They also provide semantic information (e.g. where emphasis should be placed, the definition of 
    any acronyms used, when given text is a quotation).

## Chapter 10: “Introducing CSS”
- [x] CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how
    that element should look.
- [x] Rules are made up of selectors (that specify the elements the rule applies to) and declarations 
    (that indicate what these elements should look like).
- [x] Different types of selectors allow you to target your rules at different elements.
- [x] CSS rules usually appear in a separate document, although they may appear within an HTML page.
- [x] Declarations are made up of two parts: the properties of the element that you want to change, and 
    the values of those properties. For example, the font-family property sets the choice of font, and 
    the value arial specifies Arial as the preferred typeface.

# Java book:

## Chapter 2: “Basic JavaScript Instructions”
- [x] A script is made up of a series of statements. Each statement is like a step in a recipe.
- [x] Scripts contain very precise instructions. For example, you might specify that a value must be 
    remembered before creating a calculation using that value.
- [x] Variables are used to temporarily store pieces of information used in the script.
- [x] Arrays are special types of variables that store more than one piece of related information.
- [x] JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).
- [x] Expressions evaluate into a single value.
- [x] Expressions rely on operators to calculate a value.

## Chapter 4: “Decisions and Loops”
- [x] Conditional statements allow your code to make decisions about what to do next.
- [x] Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.
- [x] Logical operators allow you to combine more than one set of comparison operators.
- [x] if ... else statements allow you to run one set of code if a condition is true, and another if it 
    is false.
- [x] switch statements allow you to compare a value against possible outcomes (and also provides a 
    default option if none match).

also here is a comparison between the if and switch statments.

    IF ... ELSE                                 |   SWITCH
                                        --------|---------
    There is no need to provide                 |   You have a default option that is run if
    an else option. (You can just               |   none of the cases match.
    use an if statement).                       |   
                                                |  
    With a series of if statements, they are    |    If a match is found, that code is run; then
    all checked even if a match has been found  |   the break statement stops the rest of
    (so it performs more slowly than switch).   |   the switch statement running (providing
                                                |   better performance than multiple if statements).


also, a list of the 7 rules for a good commit:

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how