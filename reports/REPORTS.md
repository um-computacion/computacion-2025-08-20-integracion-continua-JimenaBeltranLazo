# Automated Reports

## Coverage Report
```text
Name                 Stmts   Miss  Cover   Missing
--------------------------------------------------
core/__init__.py         0      0   100%
core/main.py             4      0   100%
tests/test_main.py       9      1    89%   14
--------------------------------------------------
TOTAL                   13      1    92%

```

## Pylint Report
```text
************* Module core.main
core/main.py:5:0: C0304: Final newline missing (missing-final-newline)
core/main.py:1:0: C0114: Missing module docstring (missing-module-docstring)
core/main.py:1:0: C0116: Missing function or method docstring (missing-function-docstring)
core/main.py:4:0: C0116: Missing function or method docstring (missing-function-docstring)
************* Module tests.test_main
tests/test_main.py:14:0: C0304: Final newline missing (missing-final-newline)
tests/test_main.py:1:0: C0114: Missing module docstring (missing-module-docstring)
tests/test_main.py:5:0: C0115: Missing class docstring (missing-class-docstring)
tests/test_main.py:7:4: C0116: Missing function or method docstring (missing-function-docstring)
tests/test_main.py:10:4: C0116: Missing function or method docstring (missing-function-docstring)

-----------------------------------
Your code has been rated at 3.08/10


```
