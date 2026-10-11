# env-loader

A tiny dotenv parser that coerces values into ints, floats and booleans.

## Why

I wanted something I could read in one sitting and vendor into a project if needed.

## Install

```bash
pip install env-loader
```

## Usage

```python
from env_loader import envLoader

result = envLoader("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
