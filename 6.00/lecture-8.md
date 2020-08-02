# Effiency

- Efficiency is about algorithms;
- Reduce a problem to a previously solved problem, thus fitting said problem into a computation and applying an already theorized algorithm.

## I. Dimensions

### a. Time
- Influenced by:
  - The speed of the machine;
  - _Cleverness_ of the implementation;
  - Input.
- Cout the number of basic steps:
T: N<sub>1</sub> -> N<sub>2</sub>

N<sub>1</sub>: corresponds to the size of the input;
N<sub>2</sub>: corresponds to the number of steps the computation will take for input of size N<sub>1</sub>;

- Steps take constant time;
- Random Access Machine (RAM):
  - Instructions are sequential;
  - Constant time required to access memory:
    - Access any memory object at in the same amount of time as any other object;

- Ways to think about the run time of an algorithm:
  1. Best case:  minimum running time over all possible inputs;
  2. Worst case: maximum running time over all possible inputs; **!**
  3. Average case: amount of running time averaged over all possible inputs;

**!** -> complexity analysis focuses on the worst case scenario:
  - provides an upper bound (_how bad can things get?_);
  - happens quite often;
  - when calculating complexity:
    - ignore constants;
    - ignore multiplicative constants;
    - use a model of assymptotic growth:
      - how the complexity grows as the limit of the size of the inputs is reached;

#### Big-O Notation
- worst case scenario;
- gives an upper bound for the assymptotic growth of the function (i.e. f(x) ∈ O(x<sup>2</sup>)
  - i.e. function `f` grows no faster than the quadratic polynomial x<sup>2</sup>
- Orders:
  - O(1): constant time
  - O(log(n))
  - O(n): linear
  - O(n log(n)): log linear
  - O(n<sup>c</sup>): polynomial
  - O(C<sup>n</sup>): exponential

 
