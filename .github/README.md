# .github Directory

This directory contains GitHub-specific configuration files and templates for the 1inch-docs repository.

## Contents

### Issue Templates (`ISSUE_TEMPLATE/`)

The repository provides several issue templates to help structure different types of issues:

- **sub-issue.md**: Template for creating sub-issues to break down larger tasks
- **bug-report.md**: Template for reporting bugs
- **feature-request.md**: Template for suggesting new features
- **config.yml**: Configuration for issue template chooser

### Documentation

- **SUB_ISSUES.md**: Comprehensive guide on how to create and manage sub-issues
- **CODEOWNERS**: Defines code owners for pull request reviews

### Workflows (`workflows/`)

GitHub Actions workflows for CI/CD:
- `pr.yml`: Continuous Integration for pull requests
- `deploy.yaml`: Deployment workflow
- `typesense.yaml`: Typesense search configuration

## Using Issue Templates

When creating a new issue, GitHub will present you with a choice of templates. Select the appropriate template for your use case:

1. **Sub-issue**: For breaking down larger issues into manageable tasks
2. **Bug report**: For reporting problems or unexpected behavior
3. **Feature request**: For suggesting new features or enhancements

For more information on managing sub-issues, see [SUB_ISSUES.md](./SUB_ISSUES.md).
