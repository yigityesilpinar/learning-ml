# A simple rest API with flask

## Prerequisites

If you haven't done yet, create a virtual env

```
python3.11 -m venv .venv
```

## Dependencies

Install poetry

```
pip install -U pip setuptools
pip install poetry
```

See [instructions](https://python-poetry.org/docs/#oh-my-zsh) for shell autocomplete.

Install deps

```
poetry install --no-root
```

## Types & Code style

Static type checking

```
poetry run mypy .
```

Code formatting

```
poetry run black .
```

## Makefile

See Makefile for common operations