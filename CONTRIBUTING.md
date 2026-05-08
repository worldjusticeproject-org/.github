# Contributing to the World Justice Project

Thank you for your interest in contributing to the World Justice Project (WJP). Contributions from researchers, developers, data scientists, and practitioners help us improve the quality, reach, and reusability of the data and tools that support the rule of law worldwide.

This document is a general guide. Individual repositories may include their own `CONTRIBUTING.md` with project-specific instructions, which take precedence over this one.

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Before You Start](#before-you-start)
- [Reporting Issues](#reporting-issues)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Submitting Changes](#submitting-changes)
- [Working with Data](#working-with-data)
- [Style and Quality](#style-and-quality)
- [Commit and Pull Request Conventions](#commit-and-pull-request-conventions)
- [Licensing of Contributions](#licensing-of-contributions)
- [Getting Help](#getting-help)

## Ways to Contribute

You don't need to write code to make a meaningful contribution. We welcome:

- 🐞 **Bug reports** — clear, reproducible reports of broken behavior.
- 💡 **Feature requests** — proposals for new functionality, indicators, or analyses.
- 📊 **Data and methodology questions** — questions or corrections about WJP data and how we measure the rule of law.
- 📝 **Documentation improvements** — fixing typos, clarifying explanations, adding examples.
- 🔬 **Research and replication** — replicating our findings, extending analyses, or sharing related work.
- 🛠️ **Code contributions** — bug fixes, refactors, performance improvements, and new features.

## Before You Start

1. **Read the project's `README`** to understand its scope, goals, and current state.
2. **Search existing issues and pull requests** to avoid duplicate work.
3. **Open an issue first** for any non-trivial change so that maintainers and other contributors can discuss the approach before code is written.
4. **Review our [Code of Conduct](./CODE_OF_CONDUCT.md)** — all contributors are expected to follow it.

## Reporting Issues

Please use the issue templates provided in each repository. A good issue includes:

- A clear, descriptive title.
- A description of the expected vs. actual behavior.
- Steps to reproduce, including operating system, language/runtime version, and relevant package versions.
- Logs, error messages, or screenshots where applicable.
- For data issues: the dataset, edition/year, country/jurisdiction, and indicator involved.

For **security vulnerabilities**, please follow our [Security Policy](./SECURITY.md) instead of opening a public issue.

## Suggesting Enhancements

When proposing a new feature, indicator, or analysis:

- Explain the problem the enhancement solves and who benefits.
- Describe how it relates to WJP's mission and existing work.
- Outline the proposed approach and any alternatives you considered.
- Note any dependencies, data sources, or methodological implications.

## Submitting Changes

1. **Fork** the repository and create a topic branch from `main` (e.g., `fix/index-typo`, `feat/add-sdg16-mapping`).
2. **Make focused changes** — one logical change per pull request keeps reviews fast and unblocks merging.
3. **Add or update tests** for any code you change. Documentation-only changes don't require tests.
4. **Update documentation** (`README`, docstrings, codebooks, methodology notes) to reflect your changes.
5. **Run the project's checks locally** (linters, formatters, tests) before opening a pull request.
6. **Open a pull request** using the project's PR template. Link the issue it addresses with `Closes #123` if applicable.
7. **Respond to review feedback** — we aim to review within a reasonable time, but please be patient with a small team.

## Working with Data

WJP publishes survey data, expert assessments, and derived indicators. When contributing to data-related projects:

- **Cite sources** clearly and preserve provenance.
- **Document units, scales, and missingness** — `0` and `NA` are not the same thing.
- **Preserve methodology** — changes to scoring, aggregation, or weighting must be discussed and approved before merging.
- **Never commit personally identifiable information (PII)** or raw survey responses that could re-identify respondents. Use the published, anonymized datasets.
- **Note edition/year** in any data file, notebook, or output.

If you find what you believe is an error in a published dataset or indicator, please open an issue using the **Data question** template before submitting changes.

## Style and Quality

Most repositories include their own style guides and tooling. As general defaults:

- **Python:** [PEP 8](https://peps.python.org/pep-0008/), formatted with [Black](https://black.readthedocs.io/) and linted with [Ruff](https://docs.astral.sh/ruff/).
- **R:** the [tidyverse style guide](https://style.tidyverse.org/), with `lintr` and `styler`.
- **JavaScript / TypeScript:** Prettier + ESLint with the project's configuration.
- **Markdown:** one sentence per line where practical, to keep diffs readable.
- **Notebooks:** clear narrative, executed cells, and outputs stripped before commit unless results are intentionally part of the artifact.

Always run the project's existing test suite before opening a PR. Add tests for new behavior.

## Commit and Pull Request Conventions

- Write commit messages in the imperative mood (e.g., *"Add EUROVOICES loader"*, not *"Added"* or *"Adds"*).
- Keep the subject line ≤ 72 characters; use the body for context, motivation, and links.
- Reference issues in the body (e.g., `Refs #45`, `Closes #87`).
- Group related commits; squash trivial fixups before merge.
- Pull request titles should be self-explanatory and follow the same conventions.

## Licensing of Contributions

Unless a repository specifies otherwise, code contributions are accepted under the repository's open-source license (typically MIT or Apache 2.0), and data and documentation contributions under the applicable [Creative Commons](https://creativecommons.org/) license. By submitting a pull request, you agree that your contribution will be released under those terms.

If your contribution requires a different licensing arrangement, please raise it in an issue before opening a pull request.

## Getting Help

- **General questions** about a project — open a GitHub Discussion or Issue in that repository.
- **Data, methodology, or research questions** — use the **Data question** or **Methodology question** issue templates.
- **Other inquiries** — email [wjp@worldjusticeproject.org](mailto:wjp@worldjusticeproject.org).

Thank you for helping advance the rule of law through open data and open code.
