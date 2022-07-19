# Question 148

Question 148 from the book Low-Level Programming, Igor Zhirkov, 2017.

## Question

What is a literal?

## Answer

In general a literal means taking words in their usual or most basic sense without metaphor or exaggeration. In computer science, a literal is a notation for representing a fixed value in source code. In C a literal is a sequence of one or more characters in the source code that represents an immediate value.

There are four different types of literals in C:

1. Integer literals, which in it most basic form uses numbers only, for example

    ```C
    60    /* Number of seconds in one minute. */
    ```

2. Floating-point Literals, indicated by either including a decimal point, an exponent part, or both, for example:

    ```C
    0.25    /* A quarter of something. */
    ```

    ```C
    1E6    /* One million, a one followed by six zeroes. */
    ```

    ```C
    7.961E9    /* World population, about eight billion.*/
    ```

3. Character literals, written using single quotes, for example:

    ```C
    'A'    /* Best grade on an exam. */
    ```

4. Null-terminated string literals, written using double quotes, for example:

    ```C
    "Hello world!"    /* A greeting from the computer. */
    ```
