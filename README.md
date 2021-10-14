# assignment3
code
(base) abrarull@TIGER01289:/mnt/c/Users/abrarull.suhel$ cd Desktop
(base) abrarull@TIGER01289:/mnt/c/Users/abrarull.suhel/Desktop$ cd pyproject.toml
(base) abrarull@TIGER01289:/mnt/c/Users/abrarull.suhel/Desktop/pyproject.toml$ black pyproject.toml
Usage: black [OPTIONS] [SRC]...
Try 'black -h' for help.

Error: Invalid value for '[SRC]...': Path 'pyproject.toml' does not exist.
(base) abrarull@TIGER01289:/mnt/c/Users/abrarull.suhel/Desktop/pyproject.toml$ black nonstandardcode.py
All done! ✨ 🍰 ✨
1 file left unchanged.
(base) abrarull@TIGER01289:/mnt/c/Users/abrarull.suhel/Desktop/pyproject.toml$ flake8 nonstandardcode.py
nonstandardcode.py:2:16: F821 undefined name 'os'
nonstandardcode.py:4:1: E402 module level import not at top of file
nonstandardcode.py:5:1: E402 module level import not at top of file
nonstandardcode.py:6:1: E402 module level import not at top of file
nonstandardcode.py:19:1: E402 module level import not at top of file
nonstandardcode.py:20:1: E402 module level import not at top of file
nonstandardcode.py:20:1: F401 'numpy as np' imported but unused
nonstandardcode.py:29:1: E402 module level import not at top of file
nonstandardcode.py:29:1: F401 'matplotlib as mpl' imported but unused
nonstandardcode.py:30:1: E402 module level import not at top of file
nonstandardcode.py:37:80: E501 line too long (81 > 79 characters)
nonstandardcode.py:38:80: E501 line too long (83 > 79 characters)
(base) abrarull@TIGER01289:/mnt/c/Users/abrarull.suhel/Desktop/pyproject.toml$ isort nonstandardcode.py
Fixing /mnt/c/Users/abrarull.suhel/Desktop/pyproject.toml/nonstandardcode.py
