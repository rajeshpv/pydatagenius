# pydatagenius

[![Release](https://img.shields.io/github/v/release/rajeshpv/pydatagenius)](https://img.shields.io/github/v/release/rajeshpv/pydatagenius)
[![Build status](https://img.shields.io/github/actions/workflow/status/rajeshpv/pydatagenius/main.yml?branch=main)](https://github.com/rajeshpv/pydatagenius/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/rajeshpv/pydatagenius/branch/main/graph/badge.svg)](https://codecov.io/gh/rajeshpv/pydatagenius)
[![Commit activity](https://img.shields.io/github/commit-activity/m/rajeshpv/pydatagenius)](https://img.shields.io/github/commit-activity/m/rajeshpv/pydatagenius)
[![License](https://img.shields.io/github/license/rajeshpv/pydatagenius)](https://img.shields.io/github/license/rajeshpv/pydatagenius)

This is a template repository for Python projects that use uv for their dependency management.

- **Github repository**: <https://github.com/rajeshpv/pydatagenius/>
- **Documentation** <https://rajeshpv.github.io/pydatagenius/>

## Getting started with your project

You are now ready to start development on your project!
The CI/CD pipeline will be triggered when you open a pull request, merge to main, or when you create a new release.

To finalize the set-up for publishing to PyPI, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/codecov/).

## Releasing a new version

- Create an API Token on [PyPI](https://pypi.org/).
- Add the API Token to your projects secrets with the name `PYPI_TOKEN` by visiting [this page](https://github.com/rajeshpv/pydatagenius/settings/secrets/actions/new).
- Create a [new release](https://github.com/rajeshpv/pydatagenius/releases/new) on Github.
- Create a new tag in the form `*.*.*`.

For more details, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/cicd/#how-to-trigger-a-release).

---

Repository initiated with [fpgmaas/cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv).
