# basic-project-setup

Basic setup for new projects.

- Prettier
- eslint-config-prettier to connect Prettier and ESLint (which is unconfigured)

- Husky hook for running prettier with lint-staged (pre-commit)
- Husky hook for commit linting to conventional commits (commit-msg)
- Husky hook preventing push to main directly (pre-push)

- GitHub Action for ensuring the PR adheres to semantic release spec
- GitHub Action for running semantic release

## Get Started

Remove .eslintrc.json

Choose your framework and install

Reinstate eslintrc.json with your preferred configuration

Setup eslint-config-prettier (https://github.com/prettier/eslint-config-prettier#installation)
