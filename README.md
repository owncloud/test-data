# Test Data

<!-- OSPO-managed README | Generated: 2026-04-16 | v2 -->

[![License](https://img.shields.io/badge/License-See%20Repository-blue.svg)](LICENSE) [![ownCloud OSPO](https://img.shields.io/badge/OSPO-ownCloud-blue)](https://kiteworks.com/opensource)

This repository provides a curated collection of sample files for use in ownCloud demo and test environments. It includes a variety of file types -- code samples, images, PDFs, documents, audio and video files -- to exercise file handling, previewing and content rendering across ownCloud installations.

> **Note:** This repository is in maintenance/legacy mode and is no longer actively developed.

## Part of Infrastructure / Tooling

This repository is part of the [ownCloud](https://github.com/owncloud) testing infrastructure. The files are used to populate demo instances and test environments with realistic content for validating file operations.

> **Legacy notice:** This repository is archived/legacy and has not been updated since 2015. It remains available for reference.

## Getting Started

Clone or download the repository to populate an ownCloud test instance with sample data:

```bash
git clone https://github.com/owncloud/test-data.git
```

Copy files into your ownCloud data directory or upload them through the web interface.

### Content Guidelines

- Only upload Creative Commons and free content
- Give credit for uploaded content within the License file
- Use the naming and crediting structure already in use

## Documentation

- [ownCloud Documentation](https://doc.owncloud.com/)

## Community & Support

**[Star](https://github.com/owncloud/test-data)** this repo and **Watch** for release notifications!

- [ownCloud Website](https://owncloud.com)
- [Community Discussions](https://github.com/orgs/owncloud/discussions)
- [Matrix Chat](https://app.element.io/#/room/#owncloud:matrix.org)
- [Documentation](https://doc.owncloud.com)
- [Enterprise Support](https://owncloud.com/contact-us/)
- [OSPO Home](https://kiteworks.com/opensource)

## Contributing

We welcome contributions! Please read the [Contributing Guidelines](CONTRIBUTING.md)
and our [Code of Conduct](CODE_OF_CONDUCT.md) before getting started.

### Workflow

- **Rebase Early, Rebase Often!** We use a rebase workflow. Always rebase on the target branch before submitting a PR.
- **Dependabot**: Automated dependency updates are managed via Dependabot. Review and merge dependency PRs promptly.
- **Signed Commits**: All commits **must** be PGP/GPG signed. See [GitHub's signing guide](https://docs.github.com/en/authentication/managing-commit-signature-verification).
- **DCO Sign-off**: Every commit must carry a `Signed-off-by` line:
  ```
  git commit -s -S -m "your commit message"
  ```
- **GitHub Actions Policy**: Workflows may only use actions that are (a) owned by `owncloud`, (b) created by GitHub (`actions/*`), or (c) verified in the GitHub Marketplace.

## Security

**Do not open a public GitHub issue for security vulnerabilities.**

Report vulnerabilities at **<https://security.owncloud.com>** -- see [SECURITY.md](SECURITY.md).

Bug bounty: [YesWeHack ownCloud Program](https://yeswehack.com/programs/owncloud-bug-bounty-program)

## License

See [LICENSE](LICENSE) for license details.

## About the ownCloud OSPO

The [Kiteworks Open Source Program Office](https://kiteworks.com/opensource), operating under
the [ownCloud](https://owncloud.com) brand, launched on May 5, 2026, to steward the open source
ecosystem around ownCloud's products. The OSPO ensures transparent governance, license compliance,
community health, and sustainable collaboration between the open source community and
[Kiteworks](https://www.kiteworks.com), which acquired ownCloud in 2023.

- **OSPO Home**: <https://kiteworks.com/opensource>
- **GitHub**: <https://github.com/owncloud>
- **ownCloud**: <https://owncloud.com>

For questions about the OSPO or licensing, contact ospo@kiteworks.com.

### License Migration to Apache 2.0

The OSPO is driving a strategic relicensing of ownCloud repositories toward the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), following
the [Apache Software Foundation's third-party license policy](https://www.apache.org/legal/resolved.html).

Individual repositories will migrate as their audit is completed. The LICENSE file
in each repo reflects its **current** license status (not the target).

**Current license: Not detected.** The OSPO will determine the current license status of this
repository before planning any migration steps. If you know the intended license, please open an
issue or contact ospo@kiteworks.com.
