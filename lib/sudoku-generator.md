# Sudoku.js

Implementation ideas borrowed from
["Solving Every Sudoku Puzzle"][norvig-sudoku] by
[Peter Norvig][norvig], and a [generator/solver][anderson-sudoku] by
[Michael Anderson][anderson].

---

```javascript
>>> sudoku.generate("easy")
```

    "easy":         62
    "medium":       53
    "hard":         44
    "very-hard":    35
    "insane":       26
    "inhuman":      17

By default, the puzzles should have unique solutions, unless you set `unique` to
false, e.g.,

```javascript
sudoku.generate("easy", false);
```
