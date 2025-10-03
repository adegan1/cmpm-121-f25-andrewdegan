# CMPM 121 Section Activity

- Name: Andrew Degan
- Date: 10/02/2025

This section activity is intended to introduce you to many of the tools and workflows that we'll use in CMPM 121, Game Development Patterns.

Key tools:

- [GitHub Codespaces](https://github.com/features/codespaces), a cloud-based development environment based [VS Code](https://code.visualstudio.com/) that runs in your web browser.
- [GitHub Actions](https://github.com/features/actions), a CI/CD service that allows you to automate your build, test, and deployment pipeline.
- [GitHub Pages](https://pages.github.com/), a static site hosting service that allows you to publish web content for free.

Key workflows:

- Learned how to use GitHub Actions
- Used GitHub codespaces to edit a program in the browser
- Utilized Deno to run a web app
- Edited starter code to make it function while making sure to use good developer practices
- Pushed repository to GitHub and made sure the live site launched without issue

## Getting Started

With Codespaces (or another environment supporting devcontainers):
3. Run `deno task dev` to start the development server

Without Codespaces (local VS Code):

1. Install the [Deno](https://docs.deno.com/runtime/getting_started/installation/) runtime.
2. Install the Deno VS Code extension (must be done only after installing Deno runtime).
3. Run `./setup-hooks.sh` to enable pre-commit quality checks
4. Run `deno task dev` to start the development server

The setup script configures Git hooks to automatically run formatting, linting, and type checking before commits.

## Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup GitHub Pages Deployment

1. Go to your repository's Settings → Pages
2. Under "Source", select "GitHub Actions"
3. The workflow will automatically deploy on pushes to the `main` branch
4. Your site will be published at `https://<your-github-username>.github.io/<repository-name>/`
