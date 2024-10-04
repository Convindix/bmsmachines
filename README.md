These are some Turing machines which simulate [Bashicu matrix system](https://googology.fandom.com/wiki/Bashicu_matrix_system), running for an extremely long time and then halting. They provide lower bounds for Busy Beaver numbers (although with very many states).

The machines were written by implementation in Adam Yedidia's language [Laconic](https://github.com/adamyedidia/parsimony), the same language used to construct the 7918-state machine which does not provably halt in ZFC. The machines themselves are all in "tm2", and are written in the following format:

```
statename:
    [symbol read] -> [next state]; [direction]; [symbol written]
```

`a` is the blank symbol, and the starting state is preceded by `START`.


