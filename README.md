# Automated Python Testing with Pytest ✅

A simple GitHub Action workflow that runs automated tests using Pytest on every push to the `main` branch. This is a learning project to understand automated testing and CI/CD basics.

## How to Use This Workflow

To use this automated workflow in your own project, follow these steps:

1.  In your repository, create a directory named `.github/workflows/`.
2.  Copy the workflow YAML file (e.g., `pytest.yml`) from this project into that directory.
3.  Commit and push the new file.

That's it. The action will now automatically run your Pytest test suite on every push to your `main` branch.

## The Workflow Explained

This repository is configured to run tests on every push to the `main` branch. The workflow performs the following steps:

1.  Checks out the repository's code.
2.  Sets up a specific version of Python.
3.  Installs Pytest.
4.  Runs the `pytest` command to discover and execute all tests.
5.  The workflow will pass if all tests succeed, or fail if any test fails.

## Technology Used

* [Python](https://www.python.org/)
* [Pytest](https://docs.pytest.org/)
* [GitHub Actions](https://github.com/features/actions)