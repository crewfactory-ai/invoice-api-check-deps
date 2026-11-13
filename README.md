# invoice-api-check-deps

The dependencies of [invoice-api](https://github.com/crewfactory-ai/invoice-api) at the tag
`v0.3.0`, installed as files for Python 3.14 on Linux x86_64
(`x86_64-manylinux_2_28`), with mypy coverage. A check that has no network puts this folder on
`PYTHONPATH`:

    PYTHONPATH=../invoice-api-check-deps python -m pytest

`PINS.txt` lists each installed package and its version. The pins are those of invoice-api's
`requirements.txt` at the same tag.
