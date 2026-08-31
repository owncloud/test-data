# AGENTS.md — test-data

## Repository Overview

A curated collection of sample files (code, images, PDFs, audio, video) for populating ownCloud demo and test environments.

- **Classification:** Infrastructure / Tooling
- **Activity Status:** Archived/Legacy (last commit 2015)
- **License:** No license detected (content should be CC/free)
- **Language:** PHP (listed but this is primarily a data repository)

## Architecture & Key Paths

- `Photos/` — Sample photo files
- `Music/` — Sample music files
- `Demo Code - C++.cc` — C++ code sample
- `Demo Code - C.c` — C code sample
- `Demo Code - PHP.php` — PHP code sample
- `Demo Code - Python.py` — Python code sample
- `Demo Image - *.jpg` — Demo images
- `Demo PDF - *.pdf` — Demo PDF files
- `Demo Movie *.mov/.ogg` — Demo video files
- `Demo MP3 - *.mp3` — Demo audio files
- `README.md` — Contribution guidelines

## Development Conventions

- Only Creative Commons and free content
- Credit uploaded content in the License file
- Follow existing naming and crediting structure

## Build & Test Commands

No build or test commands. This is a data-only repository.

## Important Constraints

- **No license file detected:** Content must be CC/free licensed. The OSPO is formalizing licensing.
- **Copyleft + Apache 2.0 migration:** Not directly applicable to this data repository, but the OSPO migration strategy applies organization-wide.
- **Archived/legacy:** Last updated in 2015; no active development.


## OSPO Policy Constraints

### GitHub Actions
- **Only** use actions owned by `owncloud`, created by GitHub (`actions/*`), verified on the GitHub Marketplace, or verified by the ownCloud Maintainers.
- Pin all actions to their full commit SHA (not tags): `uses: actions/checkout@<SHA> # vX.Y.Z`
- Never introduce actions from unverified third parties.

### Dependency Management
- Dependabot is configured for automated dependency updates.
- Review and merge Dependabot PRs as part of regular maintenance.
- Do not introduce new dependencies without discussion in an issue first.

### Git Workflow
- **Rebase policy**: Always rebase; never create merge commits. Use `git pull --rebase` and `git rebase` before pushing.
- **Signed commits**: All commits **must** be PGP/GPG signed (`git commit -S -s`).
- **DCO sign-off**: Every commit needs a `Signed-off-by` line (`git commit -s`).
- **Conventional Commits & Squash Merge**: Use the [Conventional Commits](https://www.conventionalcommits.org/) format where the repository enforces it. Many repos use squash merge, where the PR title becomes the commit message on the default branch — apply Conventional Commits format to PR titles as well. A reusable GitHub Actions workflow enforces this.

## Context for AI Agents

- This repository contains only sample data files, no code.
- No build system, CI or tests.
- Files are organized at the root level with descriptive names.
