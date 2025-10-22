# calculator.py
AST-based, safe Python calculator — CLI, GUI, and built-in tests.

# simple-calculator

Single-file safe calculator with math functions, CLI, GUI, and unit tests.

Features
- Safe AST-based expression evaluator (no eval).
- Supports operators: + - * / // % **, unary +/-, parentheses.
- Supports math functions: sin, cos, tan, asin, acos, atan, log, log10, exp, sqrt, floor, ceil, fabs, pow.
- Constants: pi, e.
- CLI (single-expression or interactive REPL), GUI (Tkinter) and built-in unittest-based tests.

Usage
- Run REPL:
  ```
  python3 calculator.py
  ```
- Evaluate single expression:
  ```
  python3 calculator.py "sin(pi/2) + 2"
  ```
- Run GUI:
  ```
  python3 calculator.py --gui
  ```
- Run built-in tests:
  ```
  python3 calculator.py --test
  ```

License
MIT (see LICENSE)
