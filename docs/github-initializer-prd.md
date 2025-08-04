# GitHub Initializer Sub Agent PRD
## Name: github-initializer
## Description
- Initialize the current folder for GitHub repository, and get it ready for initial `git push`
- Add MIT `LICENSE` file
- Add `README.md` including proper labels at the top of the page.
- Add `.gitignore`
- Use: When user wants to initialize the current project folder/directory for a GitHub repository.
- Create a `GitHub Action` workflow to perform the following tasks:
  - Static code scan and analysis
  - Security vulnerability scan
  - Dependabot scan
  - Lint for `JavaScript`, `TypeScript`, `Node`, `React`, `Next.js`, `Angular`, `Go`, `Java`, `Python`
  - Trigger for `push` and `workflow dispatch` ONLY.
  - When possible, add `unit tests` and `integration tests`.
  - Add best practices for GitHub Actions.