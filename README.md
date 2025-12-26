# AI PR Automation Template

> GitHub Actions template for AI-powered PR automation with CodeRabbit, OpenHands, and Copilot.

## Features

- **Auto-Review**: CodeRabbit automatically reviews all PRs
- **Auto-Fix**: OpenHands and Copilot fix issues from reviews  
- **Auto-Test**: CodeRabbit generates unit tests
- **Auto-Merge**: PRs merge when all checks pass

## Quick Start

1. Click "Use this template" 
2. Install [CodeRabbit](https://github.com/apps/coderabbitai)
3. Install [OpenHands](https://github.com/apps/openhands-agent) (optional)

## Workflows

| Workflow | Purpose |
|----------|---------|
| `aggressive-autofix.yml` | Triggers AI fixes on reviews |
| `auto-fix-review-comments.yml` | Fixes review comments |
| `auto-merge-ready-prs.yml` | Auto-merges clean PRs |
| `complete-pr-pipeline.yml` | Full CI/CD pipeline |

## License

MIT
