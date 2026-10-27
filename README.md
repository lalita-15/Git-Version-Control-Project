# Git Version Control Project

## Project Overview
This project demonstrates Git and GitHub best practices for version control in a DevOps workflow.

## Objectives
- Initialize and manage a Git repository.
- Create and manage main, dev, and feature branches.
- Use pull requests to review and merge changes.
- Maintain meaningful commit history.
- Use .gitignore to exclude unnecessary files.
- Create version tags for releases.
- Document project activities using Markdown.

## Tools Used
- Git
- GitHub
- Visual Studio Code
- Markdown

## Branching Strategy
- **main:** Stable and release-ready code.
- **dev:** Integration and testing branch.
- **feature/***: Development of individual changes.

## Workflow
1. Create a feature branch from dev.
2. Make changes and commit them.
3. Push the feature branch to GitHub.
4. Create a pull request into dev.
5. Merge reviewed changes into dev.
6. Create a pull request from dev into main.
7. Tag the release as v1.0.0.

## Project Structure
```text
GitOps-Version-Control-Project/
├── README.md
├── .gitignore
├── CONTRIBUTING.md
├── docs/
│   ├── git-workflow.md
│   └── task-log.md
└── scripts/
    └── hello.sh
```

## Expected Outcomes
- Practical understanding of Git branching.
- Experience with GitHub pull requests.
- Improved commit history and version management.
- Structured project documentation.

## Author
Lalita Rajpoot