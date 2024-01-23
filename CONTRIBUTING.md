
# Contributing to Fast Process Sync (FPS)

We welcome contributions to the Fast Process Sync (FPS) project and are grateful for every pull request or issue submitted. Here's how you can contribute:

## Getting Started

- First, create a fork of the repository.
- Clone your fork to your local machine.

## Branching Strategy

- `main`: The stable version of the project. All development merges here eventually.
- `dev`: Primary development branch. All feature and bugfix branches merge back into dev.
- `feature/[feature-name]`: For new features. Branch off from 'dev' and merge back when complete.
- `bugfix/[bug-name]`: For bug fixes. Branch off from 'dev' and merge back after fixing.
- `release/[version]`: For preparing releases. Created from 'dev' and merged into 'main'.
- `hotfix/[issue]`: For critical bugs in the production version. Branch from 'main', fix, and merge back.

### Workflow

1. **For New Features/Bugfixes**: Start from 'dev', create a 'feature' or 'bugfix' branch.
2. **After Completion**: Merge the branch back into 'dev' for testing.
3. **Stable 'dev'**: Create a 'release' branch, prepare for release, then merge into 'main'.
4. **For Hotfixes**: Directly address critical issues from 'main' using 'hotfix' branches.

## Making Contributions

### Reporting Issues

- Check if the issue has already been reported.
- If not, create a new issue with a clear title and description.
- Include as much relevant information as possible.

### Submitting Pull Requests

- Pull requests are the best way to propose changes.
- Push your changes to your fork and submit a pull request to the FPS repository.
- Ensure your code adheres to the existing style to maintain consistency.
- Include meaningful commit messages.
- Describe the changes and their rationale.

## Code of Conduct

- By participating, you are expected to uphold our code of conduct.
- Respectful and considerate behavior is expected from all contributors.

## Questions or Suggestions

- Feel free to open an issue if you have questions or suggestions.

Thank you for your interest in contributing to FPS!
