# How to Contribute

## Workflow

1. Create an Issue on the `pdfminer/pdfminer.six` GitHub repo.
1. Fork the `pdfminer.six` repo.
1. Clone a copy of your fork onto your local machine.
1. Create a branch off of `master` and give it a meaningful name (e.g. `my-bug-fix`).
1. Make necessary changes, commit, and push to your fork on GitHub.
1. On the `pdfminer/pdfminer.six` GitHub repo, open a Pull Request against the `develop` branch.

## Creating an Issue (Reporting a Bug)

### Before Creating an Issue

### How Do I Create a Good Issue

## Writing Your Code

### Python Style Guide

### Comments

### Tests

## Creating a Pull request

## Repository Structure

### Branches

The `master` branch represents the latest release.
All development toward a new release occurs on the `develop` branch, which is merged
to `master` when work on the release is completed.

### Tags

When the release is ready, a release Tag is then pushed to the repository.
All Tags are version numbers in YYYYMMDD format, for example 201811082.

### PyPI

All releases are published at PyPI when a versioned Tag is pushed to the repository.
The package for the release is built on the `master` branch.

## Gitter Group

## Installing from the Repository

## To Do

 * PEP-8 and PEP-257 conformance.
 * Better documentation.
 * Performance improvements.
