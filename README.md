# GitHub Extension env-to-repo

![GitHub License](https://img.shields.io/github/license/endersonmenezes/gh-env-to-repo?label=Project%20License)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/endersonmenezes/gh-env-to-repo/testing.yaml?label=Linter%20and%20Testing)
![Static Badge](https://img.shields.io/badge/build-passing-brightgreen?label=shellcheck)


The extension, called 'env-to-repo', allows you to upload an .env file from your local directory to the repository secrets on GitHub. The extension checks the existence of the .env file in the current directory and whether the user has permission to access the repository.

## Usage

```bash
# Use inside a folder with a .env file
gh env-to-repo <owner> <repo>
```

## Install

```bash
gh extension install endersonmenezes/gh-env-to-repo
```

## Upgrade Extensions

```bash
# Upgrade All with Dry Run
gh extension upgrade --all --dry-run
# Upgrade Specific with Dry Run
gh extension upgrade endersonmenezes/gh-env-to-repo --dry-run
# Upgrade All
gh extension upgrade --all
# Upgrade Specific
gh extension upgrade endersonmenezes/gh-env-to-repo
```