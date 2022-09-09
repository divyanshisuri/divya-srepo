---
layout: page
title: Collegeboard
permalink: /collegeboard/
---

# week 1 Notes
- byte: The byte data type is an 8-bit signed two's complement integer. It has a minimum value of -128 and a maximum value of 127 (inclusive). The byte data type can be useful for saving memory in large arrays, where the memory savings actually matters. They can also be used in place of int where their limits help to clarify your code; the fact that a variable's range is limited can serve as a form of documentation.

- short: The short data type is a 16-bit signed two's complement integer. It has a minimum value of -32,768 and a maximum value of 32,767 (inclusive). As with byte, the same guidelines apply: you can use a short to save memory in large arrays, in situations where the memory savings actually matters.

- int: By default, the int data type is a 32-bit signed two's complement integer, which has a minimum value of -231 and a maximum value of 231-1. In Java SE 8 and later, you can use the int data type to represent an unsigned 32-bit integer, which has a minimum value of 0 and a maximum value of 232-1. Use the Integer class to use int data type as an unsigned integer. See the section The Number Classes for more information. Static methods like compareUnsigned, divideUnsigned etc have been added to the Integer class to support the arithmetic operations for unsigned integers.

- long: The long data type is a 64-bit two's complement integer. The signed long has a minimum value of -263 and a maximum value of 263-1. In Java SE 8 and later, you can use the long data type to represent an unsigned 64-bit long, which has a minimum value of 0 and a maximum value of 264-1. Use this data type when you need a range of values wider than those provided by int. The Long class also contains methods like compareUnsigned, divideUnsigned etc to support arithmetic operations for unsigned long.

- float: The float data type is a single-precision 32-bit IEEE 754 floating point. Its range of values is beyond the scope of this discussion, but is specified in the Floating-Point Types, Formats, and Values section of the Java Language Specification. As with the recommendations for byte and short, use a float (instead of double) if you need to save memory in large arrays of floating point numbers. This data type should never be used for precise values, such as currency. For that, you will need to use the java.math.BigDecimal class instead. Numbers and Strings covers BigDecimal and other useful classes provided by the Java platform.

- double: The double data type is a double-precision 64-bit IEEE 754 floating point. Its range of values is beyond the scope of this discussion, but is specified in the Floating-Point Types, Formats, and Values section of the Java Language Specification. For decimal values, this data type is generally the default choice. As mentioned above, this data type should never be used for precise values, such as currency.

- boolean: The boolean data type has only two possible values: true and false. Use this data type for simple flags that track true/false conditions. This data type represents one bit of information, but its "size" isn't something that's precisely defined.

- char: The char data type is a single 16-bit Unicode character. It has a minimum value of '\u0000' (or 0) and a maximum value of '\uffff' (or 65,535 inclusive).

# week 2 Notes

java (code.org) learnings

variables
- in Java, variables are a mechanism to store values. There are different types of variables – the most commonly used variables are listed below:
- A boolean is one of two values: true or false. _* * Example instantiation: boolean done = false;
- An int stores whole numbers (no decimals). _* * Example instantiation: int x = 1; _* * A double stores decimals with up to 15 digits of precision. _* * Example instantiation: double y = -1.479582834;
- A String stores text using double quotes “”. _* * Example instantiation: String name = “Sam”;
the main method

main method; where program starts running
- public: The method needs to be public for the JVM to identify it.
- static: static in this context means that there will be only one type of this method and that it will be shared.
- when we call the main method, it does not require a new instantiated object – it can be called without the creation of a new object.
- void: There is nothing returned from the main method.
- main: The general signature of the main method that is identified by the JVM to execute any program from start to finish.
- String[] args: The main method’s argument (or input parameter) is an array of type String. This allows the method to accept command line arguments, which are stored as Strings in this variable. The name args can be changed.
inheritance

superclass: the class that the new class inherits from is generally called the parent or super class
- subclass: the class that inherits from the superclass
- We use the extends keyword to explicitly state the superclass.

This website is powered by **[fastpages](https://github.com/fastai/fastpages)** [^1].



[^1]:a blogging platform that natively supports Jupyter notebooks in addition to other formats.
