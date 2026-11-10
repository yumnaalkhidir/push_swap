# push_swap

A program that sorts a stack of integers using two stacks (`a` and `b`) and a restricted set of operations, aiming for as few moves as possible.

## Concepts covered
- Stack data structures and a restricted instruction set: `sa sb ss pa pb ra rb rr rra rrb rrr`
- A cost-based insertion algorithm: each number is given a cost to move to stack `b` and back to the right position in `a`, and the cheapest move is executed first
- A special-cased fast path for 2-3 element stacks

## Build & run
```sh
make
./push_swap 2 1 3 6 5 8
```
Prints the sequence of operations that sorts the input.

---
Part of the 42 School curriculum.
