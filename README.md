# ESLint GitHub Actions workflow

This is an ESLint workflow that runs on pull request, lints all JS files and comments the ESLint report on the PR

## Setup

Setup is very easy.

1. Move lint.yml to .github/workflows/lint.yml (you can name it anything you like, for example: lint_pr.yml, just make sure it's under the .github/workflows directory)

2. Move create-md-message.js to ci/create-md-message.js