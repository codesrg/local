# local

[![PyPI](https://img.shields.io/pypi/v/local)](https://pypi.python.org/pypi/local)
[![Pypi - License](https://img.shields.io/github/license/codesrg/local)](https://github.com/codesrg/local/blob/main/LICENSE)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/local?color=red)](https://pypi.python.org/pypi/local)

To browse local files.

## Installation

`pip install -U local`

## Usage

```
usage: local [options]

optional arguments:
  -h, --help       show this help message and exit
  -v, --version    show version number and exit.

to browse local files:
  keys             keyword to search
  -p , --path      root path
  -n, --no-prompt  do not interactively prompt for choice
```

### Python Script

To browse local files.

```python
from local import Local

loc = Local("../path").search("key", "words")
loc.display()  # to display results
loc.open("category-index")  # to open specified file/folder
```

### Command Line

To browse local files.

```
$ local "key" "word" --path "/"
### matched results ###
```

## Issues:

If you encounter any problems, please file an [issue](https://github.com/codesrg/local/issues) along with a detailed
description.