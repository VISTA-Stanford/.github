<!--

This source file is part of the Stanford VISTA projects

SPDX-FileCopyrightText: 2025 Stanford University and the project authors (see AUTHORS.md)

SPDX-License-Identifier: MIT

-->

# Contributing Guidelines to the Stanford VISTA projects.

Thank you for contributing to the Stanford VISTA projects! Your contributions help us advance our research and maintain high-quality code. Below are the guidelines to ensure that contributions are made efficiently, with consistency and respect for our lab's values. Our mission is to provide readable, maintainable, and reproducible code.


## General Contribution Process
We require all contributors to follow the [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow). Issues should be created to track bugs or document major decisions. The only way to propose changes to the codebase is by using pull requests.

If you are contributing to an existing project, you should use a fork unless you are part of the core team. However, if you are starting a new project, you may create a new repository within the organization, provided it follows the general guidelines outlined here. Make sure to discuss your new repository with the core team before initiating it, and ensure that it aligns with the lab’s research goals. All new repositories must follow the same structure and standards as existing repositories, including code style, documentation, and testing.

When your code or project is ready, open a pull request (PR) from your fork or repository to the main repository. Ensure that the PR provides a proper description, tags related issues, and links to any relevant GitHub discussions. You MUST use the provided PR template for consistency.

## GitHub Account & Commit Signing
Each contribution requires a [GitHub account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github). We recommend that you add your full name, a profile picture, and preferred pronouns to your GitHub account to make it easier to recognize and address you in commits. 

> [!IMPORTANT]  
> **Note**: Ensure that you set up commit signature verification **before** your first commit, as outlined in the [GitHub documentation](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification).



## Code Formatting and Style
Contributors are expected to follow established guidelines for code style, such as [PEP 8](https://peps.python.org/pep-0008/) for Python. Descriptive and clear names should be used for variables, and snake_case should be preferred for naming functions and variables. Comments should be included where necessary, and comprehensive docstrings, following the [Google Style guide](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html), should be provided for all functions, classes, and modules.


## Repository Creation and Pull Requests
For contributors starting a new project, you may create a new repository under the lab’s GitHub organization. Ensure that the project aligns with the lab's goals and discuss its scope with the core team before proceeding. All new repositories must adhere to the lab’s standards for documentation, code style, and testing.

For contributors working on an existing repository, you must [fork the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) and work on your changes there. Once your changes are ready, submit a pull request with a detailed description. Make sure to follow the [steps outlined for creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork). Include a detailed description and use the PR template provided (https://github.com/DaneshjouLab/.github/blob/main/.github/pull_request_template.md). Request a review from a core team member and ensure that your PR is properly labeled and linked to any relevant issues or discussions.

## Testing and CI/CD
Every new contribution must be tested properly, and automatic verification should be done through unit tests, and the continuous integration (CI) setup that is in place using GitHub Actions. Before submitting your pull request, please ensure that all tests pass. We recommend that testing coverage reaches at least 80%.

## Documentation
All new contributions must be properly documented. You are encouraged to use in-line comments, docstrings, and external documentation where necessary to ensure clarity.

## Licensing and Attribution
We use the [REUSE Software Conventions](https://reuse.software) to structure our attributions and contributor lists.
Your contributions must comply with the licensing used by the repository. A proper header must be included in every file, indicating attribution and license information as follows:

```
This source file is part of the Stanford VISTA projects

SPDX-FileCopyrightText: 2025 Stanford University and the project authors (see AUTHORS.md)

SPDX-License-Identifier: MIT
```

You must provide proper attribution to any external sources if your contribution is based on work from other projects.


## Feature Proposition and Bug Reporting Policy
We use GitHub Issues to track and manage work items efficiently.

- Reporting Bugs: If you encounter a bug, please report it by opening a new issue and using the bug report template provided (ISSUE_TEMPLATE/bug_report.md).
- Proposing New Features: If you have an idea for a new feature, open a new issue and select one of the relevant templates: feature request (ISSUE_TEMPLATE/feature_request.md) or enhancement (ISSUE_TEMPLATE/enhancement.md).


## Programming Language-Specific Setups
We encourage contributors to work in their preferred programming languages. Although many aspects are common across projects, some systems require language-specific setups to facilitate contribution, testing, and documentation. You should follow the best practices and specific setups relevant to the programming language used in the project you are contributing to.

