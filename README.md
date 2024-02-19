# GitHub Extension env-to-repo

This GitHub Extension allow you to use gh cli to fast set a repository secrets from a .env file.

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