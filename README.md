# .github

This repository serves as the central location for shared GitHub templates, workflows, and documentation across the **miccy-dev** organization.

## Purpose

The `.github` repository enables the organization to standardize and share:

- **Issue and Pull Request Templates**  
  Create unified templates for issues and pull requests that apply to all repositories within the organization.
- **GitHub Actions Workflows**  
  Share reusable workflows for automation (CI/CD, linting, code quality checks, etc.) across multiple repositories.
- **Organization-Wide Documentation**  
  Host general guidelines, rules, contributing guides, and other documentation relevant to all projects.

## Repository Structure

```text
.github/
│
├── ISSUE_TEMPLATE/         # Issue templates
│   └── bug_report.md
│   └── feature_request.md
│
├── PULL_REQUEST_TEMPLATE/  # Pull request templates
│   └── pull_request_template.md
│
├── workflows/              # Shared GitHub Actions workflows
│   └── ci.yml
│
├── CONTRIBUTING.md         # Contribution guidelines
├── CODE_OF_CONDUCT.md      # Code of Conduct
└── README.md               # This file
```

## Best Practices

- **Keep templates and workflows as generic as possible** to maximize reusability across different repositories.
- **Update templates and workflows regularly** to match the evolving needs of your team or organization.
- **Use clear and concise language** in both templates and documentation.
- **Propose all changes via pull requests** and leverage code review for improvements.

## Further Resources

- [GitHub Docs: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [Organization-level Copilot custom instructions](https://docs.github.com/en/copilot/customizing-copilot/adding-organization-custom-instructions-for-github-copilot)

---

> This repository is strictly for organizational purposes. Please do not add project source code here.
