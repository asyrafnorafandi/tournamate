# Contributing to TournaMate

First off, thank you for considering contributing to this project! Your time and effort are greatly appreciated.

The following is a set of guidelines to help you contribute effectively to the project. Please adhere to these guidelines to make the contribution process smooth and efficient for everyone involved.

---

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [How to Contribute](#how-to-contribute)
   - [Reporting Bugs](#reporting-bugs)
   - [Suggesting Features](#suggesting-features)
   - [Creating Pull Requests](#creating-pull-requests)
3. [Development Setup](#development-setup)
4. [Coding Guidelines](#coding-guidelines)
5. [Testing](#testing)

---

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to asyrafnorafandi@gmail.com.

---

## How to Contribute

### Reporting Bugs

If you encounter a bug in the project, feel free to open a [bug report](.github/ISSUE_TEMPLATE/bug_report.md). Please include the following details:

- A clear description of the issue.
- Steps to reproduce the bug.
- Information about your environment (OS, browser, Next.js version, etc.).
- Screenshots, if applicable.

### Suggesting Features

If you have an idea for a new feature, we’d love to hear about it! Open a [feature request](.github/ISSUE_TEMPLATE/feature_request.md) and provide:

- A description of the feature.
- The problem it solves or the value it adds.
- Any alternatives or related features.

### Creating Pull Requests

When making a contribution through a pull request (PR):

1. **Fork** the repository and create your branch from `main`.
2. **Run** the tests to ensure your changes do not break existing code.
3. **Create** your pull request with the following in mind:
   - Include a clear description of what the PR changes.
   - Reference the issue number your PR is related to (if applicable).
   - Ensure that your changes follow the [Coding Guidelines](#coding-guidelines).
4. Be sure to fill out the provided PR template thoroughly.

---

## Development Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/asyrafnorafandi/tournamate.git
   cd tournamate
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000` to see your changes live.

---

## Coding Guidelines

To ensure consistency across the codebase, please adhere to the following standards:

- **Code Formatting:** This project uses [Prettier](https://prettier.io/) for code formatting. You can run the following command to format your code:

  ```bash
  npm run format
  ```

- **Linting:** Before pushing changes, ensure your code passes linting:

  ```bash
  npm run lint
  ```

- **Commit Messages:** Follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commit messages. For example:
  - `fix: resolve navbar alignment issue`
  - `feat: add user authentication`

---

## Testing

Please make sure all tests pass before submitting a PR. If you add new functionality, include corresponding unit/integration tests.

- **Run Tests:**

  ```bash
  npm test
  ```

- **End-to-End Testing:** If applicable, ensure your changes work across various environments by adding E2E tests.

---

Thank you again for your contribution! If you have any questions, feel free to open an issue or reach out to asyrafnorafandi@gmail.com.
