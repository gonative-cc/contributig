# Contribute to Native

This repository contains shared resources about contribution and security policies:

- [Contributor Code of Conduct](CODE_OF_CONDUCT.md)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Security and Reporting](SECURITY.md)

## Developer Certificate of Origin

The Developer Certificate of Origin (DCO) is a lightweight way for contributors to certify that they wrote or otherwise have the right to submit the code they are contributing to the project. See the [full text of the DCO](DCO.txt).

**We require all contributors** to affirm [Developer Certificate of Origin](https://developercertificate.org/) (DCO) on Pull Requests. It requires all commit messages to contain the Signed-off-by line with an email address that matches the commit author. You can accomplish this by either:

- Set `commit.gpgsign = true` in your `.gitconfig`. The easiest way is to set it globally: `git config --global commit.gpgsign true`.
- add `-S` option when running `git` command, eg: `git commit -S -m "YOUR_COMMIT_MESSAGE"`
- [Adding signing key](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits) to your GitHub, for commits done through GitHub.
