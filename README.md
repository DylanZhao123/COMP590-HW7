# Assignment 7: Collatz Sequence

Functional Rust implementation of Collatz sequence functions.

## Functions

- `collatz_length(n)`: Returns the number of steps in the Collatz sequence starting from n
- `longest_collatz(limit)`: Finds the starting number below limit with the longest sequence

## Running

```bash
rustc -O main.rs && ./main
```

The `-O` flag is required for tail call optimization to prevent stack overflow on large inputs.

## Authors

- Qianlin Cui
- Dylan Zhao
