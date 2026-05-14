# JavaScript Basics Lecture 1 Notes

In JavaScript, you should default to `const` and only switch to `let` when
the value needs to change. This helps prevent accidental reassignment and
makes your code easier to read.

## Code I tried in the REPL

```javascript
const x = 5;
let y;
y = 5;
0.1 + 0.2
let u = null;
u = 5;
5 / 0
let i;
i == null;
i === null;
```

## Output

```
undefined
undefined
5
0.30000000000000004
undefined
5
Infinity
undefined
true
false
```

## Key things I learned

- `const` must be initialized when declared.
- Use `const` by default; only switch to `let` when the value needs to change
