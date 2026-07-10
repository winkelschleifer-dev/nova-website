# Nova Language website

This repository contains the official website and documentation for Nova, an experimental programming language focused on readable, human-friendly code.

## About Nova

Nova is being designed as a simple language with room to grow. Its goal is to combine the readability associated with Python with explicit types and future capabilities inspired by languages such as C++.

The project is in early development, so its syntax and implementation may change.

## Syntax preview

```nova
$ A comment

make int x = 1
make str message = "Value of x:"

set x += 1
say "Value of x is {x}"
```

Nova uses short English keywords:

- `make` creates a variable;
- `set` changes a variable;
- `say` prints output;
- `$` begins a comment.

## Project repositories

- [Interpreter](https://github.com/winkelschleifer-dev/nova)
- [Website](https://github.com/winkelschleifer-dev/nova-website)

## Status

The Nova interpreter is a prototype written in Python. Basic source-file reading and variable-declaration parsing are under active development. Features such as expressions, interpolation, control flow, functions, lists, and OOP are planned.
