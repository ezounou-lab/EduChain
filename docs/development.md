# Development Guide

## Overview

This guide explains the basic development workflow for contributing to EduChain.

The goal is to keep development organized, consistent, and easy to follow for both beginners and experienced developers.

## Development Workflow

A typical contribution follows these steps:

1. Clone the repository.
2. Create a dedicated branch.
3. Make the required changes.
4. Test the changes.
5. Commit the changes.
6. Push the branch to GitHub.
7. Open a Pull Request.

## 1. Create a Branch

Before making changes, create a new branch:

```bash
git checkout -b feature/my-feature
```

Use a descriptive branch name that explains the purpose of the work.

Examples:

```text
feature/add-learning-module
fix/login-error
docs/update-installation
```

## 2. Make Your Changes

Modify the project files according to the purpose of your branch.

Keep changes focused and avoid modifying unrelated parts of the project.

## 3. Test Your Changes

Before committing, verify that your changes work correctly.

Run the appropriate tests or checks defined by the project.

Testing helps prevent bugs from being introduced into the main branch.

## 4. Commit Your Changes

Create a clear commit message:

```bash
git add .
git commit -m "feat: add new learning module"
```

Commit messages should briefly describe what changed.

## 5. Push Your Branch

Push the branch to GitHub:

```bash
git push origin feature/my-feature
```

## 6. Create a Pull Request

After pushing the branch, open a Pull Request on GitHub.

The Pull Request should explain:

* what was changed;
* why the change was made;
* how it was tested;
* any relevant limitations or known issues.

## Code Quality

Contributors should aim to write code that is:

* readable;
* simple;
* maintainable;
* properly documented;
* consistent with the existing project structure.

## Documentation

Technical changes should be accompanied by documentation updates when necessary.

Documentation is considered part of the project, not an optional addition.

## Future Development Rules

As EduChain grows, additional development standards may be introduced, including:

* coding conventions;
* testing requirements;
* branch naming conventions;
* commit message conventions;
* Pull Request templates;
* code review guidelines.

These rules will be documented here as the project evolves.
