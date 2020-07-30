# Introduction to 6.00

## I. Knowledge
### a. Declarative Knowledge
- Composed of factual statements;
- Give you a way of testing things but not how to accomplish them;

**Example:**
> y is the square root of x if and only if y*y=x

### b. Imperative Knowledge
- Tells you how to accomplish something, thus it's pretty much an algorithm[^1];

**Example:**
Compute an approximation to the square root of x.
1. Start with a guess, g;
2. If g*g is *close enough* to x, then g is a good approximation of the square root of x;
3. Otherwise, create a new guess: ![](https://i.imgur.com/6P5uC4r.gif);
4. Go back to step 2.

---

## II. Types of Computers
### a. Stored-Program Computer (SPC)
- Treats data and instructions as the same thing;
![Logical organization of a computer](https://i.imgur.com/TuxZoaY.jpeg)
- The image above represents a computer with a von Neumann architecture, thus we can say that SPC is, infact, a synonym for von Neumman architecture.

---

## III. S-SS-S
### a. Syntax
- Sequence of characters and symbols that constitute a well-formed string;
- Language-specific constraint on how to express static semantics;

**Example:**
```py
x = 3+1 # valid syntax
x = 3/"abc" # valid syntax
```

### b. Static Semantics
- Checks whether a well-formed string has meaning;
**Example:**

```py
x = 3+1 # valid syntax and static semantics
x = 3/"abc" # valid syntax (VALUE OPERATOR VALUE) but incorrect static semantics
```

### c. Semantics
- The meaning of the well-formed, syntactically and static semantic correct stringM
**Example:**

```py
x = 3+1 # x is 4
```

---

## IV. Compiled vs. Interpreted
### a. Compiled
- `source code -> checker -> interpreter -> output`
- `source code -> checker/compiler -> object code -> interpreter -> output

---

[^1]: a process or set of rules to be followed in calculations or other problem-solving operations, especially by a computer.
