# cz-pydata

[![PyPI - Version](https://img.shields.io/pypi/v/cz-pydata.svg)](https://pypi.org/project/cz-pydata)
[![PyPI - Python Versions](https://img.shields.io/pypi/pyversions/cz-pydata.svg)](https://pypi.org/project/cz-pydata)

-----

[Commitizen](https://commitizen-tools.github.io/commitizen/) is command-line utility
that helps you create your own set of rules for generating consistent commits,
bumping your project's version, or generating a change log automatically.

[PyData](https://pydata.org/project/) is an umbrella of projects from the scientific Python community,
including NumPy, SciPy and Pandas. Some of these projects are using a commit message convention derived from the [NumPy development guide](https://numpy.org/doc/stable/dev/development_workflow.html#writing-the-commit-message), which will be referred to as the _PyData convention_.

[Keep a Changelog](https://keepachangelog.com/) is a specification for writing structured
and human-readable changelogs. To my knowledge, there is currently no tooling available
to turn PyData-style commit messages into a structured changelog automatically. 

This plugin extends Commitizen to:
- Understand or generate commit messages following the PyData convention.
- Bump semantic versioning of a project based on those commit messages.
- Generate a structured changelog automatically following the KaC spec.

**Table of Contents**

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation

```console
pip install cz-pydata
```

## Usage

```console
cz --name cz_pydata <command>
```

## License

`cz-pydata` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
