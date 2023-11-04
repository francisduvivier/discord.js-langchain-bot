# Local LLM Discord Bot for Hacker Spaces

![Python](https://img.shields.io/badge/python-3.11+-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build](https://github.com/francisduvivier/discord-local-llm-bot/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/francisduvivier/discord-local-llm-bot/actions/workflows/test.yml)
[![codecov](https://codecov.io/gh/francisduvivier/discord-local-llm-bot/branch/master/graph/badge.svg)](https://codecov.io/gh/francisduvivier/discord-local-llm-bot)

## Template For Python Projects

This is a template for Python projects. What you get:

- Source code and test code is separated in different directories.
- External libraries installed and managed by [Pip](https://pypi.org/project/pip/) and [setuptools](https://setuptools.pypa.io/en/latest/) in a pyproject.toml.
- Setup for tests using [Pytest](https://docs.pytest.org/en/stable/) and coverage with [Pytest-Cov](https://github.com/pytest-dev/pytest-cov).
- Continuous testing with [Github-Actions](https://github.com/features/actions/) including [pre-commit](https://github.com/pre-commit/pre-commit).
- Code coverage reports, including automatic upload to [Codecov](https://codecov.io).
- Code documentation with [Mkdocs](https://www.mkdocs.org/).

## Structure

``` text
├── pyproject.toml
├── ... other config files ...
├── docs
│   ├── api.md
│   └── index.md
├── langchainOllama
│   ├── __init__.py
│   ├── ollama.py
└── tests
    ├── __init__.py
    └── test_langchainOllama.py
```

### Commands

```bash
# Build and Install (local)
pip install -e .
## or
pip install -e ../Python-Project-Template
## or
pip install -e ../Python-Project-Template[all]
```

```bash
# Test
pytest tests  # OR
pytest .  # OR
pytest
```

```bash
# Code Coverage
pytest --cov=discordbot tests --cov-report=html
```
