# Example Python Package

Following this article: https://mathspp.com/blog/how-to-create-a-python-package-in-2022

[![PyPI version][pypi-image]][pypi-url]
[![Build status][build-image]][build-url]
[![Code coverage][coverage-image]][coverage-url]
[![GitHub stars][stars-image]][stars-url]
[![Support Python versions][versions-image]][versions-url]

## Notes

**ZSH**
In zsh, it looks like you need to quote poetry packages:

```
poetry add -D scriv[toml]
$ zsh: no matches found: scriv[toml]
```

```
poetry add -D "scriv[toml]"
$ ... installed ...
```

## Changelog

Refer to the [CHANGELOG.md](CHANGELOG.md) file.


<!-- Badges -->

[pypi-image]: https://img.shields.io/pypi/v/pypy_geoff
[pypi-url]: https://pypi.org/project/pypy_geoff/
[build-image]: https://github.com/geoffdutton/pypy_geoff/actions/workflows/build.yaml/badge.svg
[build-url]: https://github.com/geoffdutton/pypy_geoff/actions/workflows/build.yaml
[coverage-image]: https://codecov.io/gh/geoffdutton/pypy_geoff/branch/main/graph/badge.svg
[coverage-url]: https://codecov.io/gh/geoffdutton/pypy_geoff/
[stars-image]: https://img.shields.io/github/stars/geoffdutton/pypy_geoff
[stars-url]: https://github.com/geoffdutton/pypy_geoff
[versions-image]: https://img.shields.io/pypi/pyversions/pypy_geoff
[versions-url]: https://pypi.org/project/pypy_geoff/
