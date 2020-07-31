# Machine Interpretation of a Program

## I. Functions
- A language  mechanism that provides two things:
	1. Decomposition:
		- Creates structure;
		- Breaks the program into modules (self-contained and reusable);
	2. Abstraction:
		- Suppresses implementation details;

```py
def f(x):
	x = x+1
	print(f'x @ f(x) = {x}') # x + 1
	return x;

x = 3
z = f(x)
print(z) # 3+1
print(x) # 3
```

**Function call flow:**
1. The formal parameter, `x`, is _bound_ to the value of the _actual_ parameter, `x`;
2. Upon entry of a function, a new _scope_<sup>1</sup> is created:
	- Variables declared inside a scope are only accessible inside that scope.
---

### Footnotes
[1]: A mapping from names to objects;
