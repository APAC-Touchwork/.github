# Contributing

Thank you for your interest in contributing! Please read this guide before submitting issues or pull requests.

## Getting Started

1. **Fork** the repository to your own GitHub account.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
3. Create a new branch from `main` (or the relevant base branch):
   ```bash
   git checkout -b feature/my-new-feature
   ```

## Branch Naming Conventions

Use the following prefixes for branch names:

| Prefix | Purpose |
|--------|---------|
| `feature/` | New features or enhancements |
| `bugfix/` | Bug fixes |
| `hotfix/` | Urgent production fixes |
| `chore/` | Maintenance tasks, dependency updates |
| `docs/` | Documentation changes only |

**Example:** `feature/add-user-authentication`, `bugfix/fix-login-redirect`

## Commit Message Conventions

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.

**Format:**
```
<type>(<optional scope>): <short description>

[optional body]

[optional footer(s)]
```

**Types:**

| Type | When to use |
|------|------------|
| `feat` | A new feature |
| `fix` | A bug fix |
| `chore` | Maintenance, tooling, or dependency changes |
| `docs` | Documentation only changes |
| `refactor` | Code restructuring with no behaviour change |
| `test` | Adding or updating tests |
| `style` | Formatting, whitespace (no logic changes) |
| `ci` | CI/CD configuration changes |
| `perf` | Performance improvements |
| `revert` | Reverting a previous commit |

**Examples:**
```
feat(auth): add OAuth2 login support
fix(api): handle null response from payment gateway
docs: update README with setup instructions
chore(deps): upgrade lodash to 4.17.21
```

## Opening a Pull Request

1. Push your branch to your fork:
   ```bash
   git push origin feature/my-new-feature
   ```
2. Open a pull request against the `main` branch of the upstream repository.
3. Fill in the [pull request template](/.github/PULL_REQUEST_TEMPLATE.md) fully.
4. Link any related issues using `Closes #<issue-number>`.

## Pull Request Review Process

- All pull requests require at least **one approving review** before merging.
- A reviewer may request changes — please address all comments or discuss them before re-requesting review.
- Keep pull requests focused and small where possible. Large PRs are harder to review and slower to merge.
- CI checks must pass before a PR can be merged.
- Squash commits are preferred when merging to keep the history clean.

## Coding Standards

<!-- TODO: Add link to coding standards documentation once defined. Coding standards will be documented per-repository or in a shared standards document and linked here. -->

Coding standards will be added at a later date and linked here. In the meantime, follow existing patterns in the codebase and ensure your code is clean, readable, and tested.

## Reporting Bugs or Requesting Features

Use the issue templates to report bugs or request features:

- 🐛 [Bug Report](/.github/ISSUE_TEMPLATE/bug_report.md)
- ✨ [Feature Request](/.github/ISSUE_TEMPLATE/feature_request.md)
- 📋 [General Issue / Task](/.github/ISSUE_TEMPLATE/general_issue.md)
