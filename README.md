# ochresjumpier5e-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m ochresjumpier5e_kit.cli --help
```

```python
from ochresjumpier5e_kit.core import Ochresjumpier5eTool

tool = Ochresjumpier5eTool()
print(tool)
```

## Layout

```
ochresjumpier5e_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 ochresjumpier5e
