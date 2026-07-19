<div align="center">
  <h1>Butian Engineering Club · GitHub defaults</h1>
  <p>English | <a href="README.zh-Hans.md">简体中文</a></p>
  <p>
    <img src="https://img.shields.io/github/last-commit/butian-club/.github?style=flat-square" alt="last commit" />
    <img src="https://img.shields.io/github/license/butian-club/.github?style=flat-square" alt="license" />
  </p>
</div>

## Project Introduction

Shared GitHub profile and community-health defaults for the Butian Engineering Club.
Repositories in the organization inherit the issue templates, pull-request checklist,
contribution guide, and security policy from this single source.

## Project Features

🏠 **Organization profile** — `profile/README.md` is rendered on the organization page,
with a complete Simplified Chinese counterpart.

📮 **Contribution defaults** — bilingual issue templates, a pull-request checklist, and
shared contributor guidance keep collaboration actionable across repositories.

🔒 **Security policy** — vulnerability reports are directed to GitHub's private reporting
channel instead of public issues.

## Getting Started

GitHub applies these files automatically to organization repositories that do not contain a
local file of the same type. A repository can override a default by adding its own file. Any
file under a repository's `.github/ISSUE_TEMPLATE/` directory overrides the entire inherited
issue-template directory.

## Project Structure

```bash
.github/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md           # shared bug report
│   │   ├── config.yml              # issue creation settings
│   │   └── feature_request.md      # shared feature request
│   ├── CONTRIBUTING.md             # contribution workflow
│   ├── PULL_REQUEST_TEMPLATE.md    # pull-request checklist
│   └── SECURITY.md                 # private vulnerability reporting
├── profile/
│   ├── README.md                   # English organization profile
│   └── README.zh-Hans.md           # Simplified Chinese organization profile
├── .gitignore                      # ignored local files
├── LICENSE                         # code license
├── README.md                       # English documentation
└── README.zh-Hans.md               # Simplified Chinese documentation
```

## License

This project's code is licensed under [MIT License](LICENSE).
