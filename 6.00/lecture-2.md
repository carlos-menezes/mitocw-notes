# Core Elements of a Program

## I. Operator Overloading
- Overloaded operators have a meaning that depends upon the type of operands;
- Languages do type-checking in order to reduce the probability that the programmer will write a program with a meaning that will surprise the author;

**Examples:**
```py
3+3 # 6 -> sum
'a' + 'b' # 'aa' -> concatenation
'a' + 3 # static semantic error
```

---

## II. Branching Programs
- Every step is executed, at most, once;
- The length of program (in terms of lines) is *roughly*[^2] directly proportional to the amount of time it will take to execute the program.
- These programs are somewhat limited;

---

## Problem I
Write a program that does the following in order:
1. Asks the user to enter his/her date of birth.
2. Asks the user to enter his/her last name.
3. Prints out the user's last name and date of birth, in that order.

```py
birth = input("Enter your birthdate (dd/mm/yyyy): ")
surname = input("Enter your surname: ")

print(f'{surname} {birth}')
```


[^2]: Some instructions take more (or less) time than others.
