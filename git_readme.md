# Secret Detection Tools

## General Secret Scanning for Filesystems and Git Repositories
- **[Nosey Parker](https://github.com/praetorian-inc/noseyparker)**: Rapidly scans file systems and Git repositories for sensitive information using high-performance regular expression matching.
- **[Gitleaks](https://github.com/gitleaks/gitleaks)**: An open-source solution that scans Git repositories for hardcoded secrets using regular expressions and entropy checks.

## Advanced Git Repository Secret Scanning
- **[TruffleHog](https://github.com/trufflesecurity/trufflehog)**: Searches Git repositories for high-entropy strings and predefined secret patterns to uncover hidden credentials and API keys.
- **[GitHound](https://github.com/tillson/git-hound)**: A reconnaissance tool for finding exposed API keys and sensitive data across GitHub, using pattern matching and commit history analysis.

## Pre-Commit and Pre-Push Secret Protection
- **[Talisman](https://github.com/thoughtworks/talisman)**: Prevents committing sensitive information to Git repositories by scanning for secrets during pre-commit and pre-push hooks.
- **[Git-Secrets](https://github.com/awslabs/git-secrets)**: Prevents committing sensitive information to Git repositories by scanning for patterns like AWS credentials and custom secrets in commit history and hooks.
- **[detect-secrets](https://github.com/Yelp/detect-secrets)**: A tool from Yelp that acts as a pre-commit hook, systematically preventing new secrets from entering your codebase.

## Windows File Share Secret Scanning
- **[Snaffler](https://github.com/SnaffCon/Snaffler)**: Designed for penetration testers, this tool scans Windows file shares for sensitive information like passwords and certificates.
