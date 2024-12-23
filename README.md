![Logo!](assets/logo.png)

# Contribute to Native

This repository contains shared resources about contribution and security policies:

- [Contributor Code of Conduct](CODE_OF_CONDUCT.md)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Security and Reporting](SECURITY.md)
- [Best practices: Go](best-practices-go.md)

## Developer Certificate of Origin

The Developer Certificate of Origin (DCO) is a lightweight way for contributors to certify that they wrote or otherwise have the right to submit the code they are contributing to the project. See the [full text of the DCO](DCO.txt).

**We require all contributors** to affirm [Developer Certificate of Origin](https://developercertificate.org/) (DCO) on Pull Requests. It requires:

1. all commit **messages** to contain the Signed-off-by line with an email address that matches the commit author: `Signed-off-by: Author Name <authoremail@example.com>`. You can do this automatically by using the -s flag (i.e., `git commit -s`). Example message:

   ```
   This is my commit message

   Signed-off-by: Random J Developer <random@developer.example.org>
   ```

   - To add your Signed-off-by line to every commit in your branch you can run

     ```
     git rebase HEAD~<number of commits in your branch> --signoff
     git push --force-with-lease
     ```

2. Sign all your commits. You can accomplish this by:

   - Set `commit.gpgsign = true` in your `.gitconfig`. The easiest way is to set it globally: `git config --global commit.gpgsign true`.
   - add `-S` option when running `git` command, eg: `git commit -S -m "YOUR_COMMIT_MESSAGE"`
   - [Adding signing key](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits) to your GitHub, for commits done through GitHub.
