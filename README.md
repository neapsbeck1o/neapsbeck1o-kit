# neapsbeck1o-kit

Sort a folder of files into per-type subfolders.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m neapsbeck1o_kit.cli --help
```

```python
from neapsbeck1o_kit.core import Neapsbeck1oTool

tool = Neapsbeck1oTool()
print(tool)
```

## Layout

```
neapsbeck1o_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 neapsbeck1o
