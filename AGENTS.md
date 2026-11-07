# Repository Guidelines

## Project Structure & Module Organization

This repository currently contains no application source, tests, or assets. Keep new work organized by purpose: place implementation under a clearly named source directory (such as `src/`), automated checks under `tests/` or alongside modules where the chosen framework expects them, and static files under `assets/` or `public/`. Update this guide when the project adopts a concrete structure so paths and commands remain accurate.

## Build, Test, and Development Commands

No build system or development scripts are configured yet. When introducing a language or framework, add its standard project manifest and document reproducible commands here. Prefer project-local scripts—for example, `npm run dev`, `npm test`, or `make build`—and state what each command does. Run the relevant checks before submitting changes.

## Coding Style & Naming Conventions

Follow the formatter and lint rules selected by the project; do not introduce a competing style tool without a project need. Use consistent indentation within each language, descriptive names, and the established naming patterns of neighboring files. Keep modules focused and avoid committing generated output or local environment files.

## Testing Guidelines

There is no test framework or coverage requirement configured yet. Add tests with new behavior and bug fixes when a test framework is established. Name tests so their subject and expected behavior are clear (for example, `test_<behavior>` or `<module>.test.<ext>`), and record the exact test command in the project manifest and this guide.

## Commit & Pull Request Guidelines

No commit history is available to establish a repository-specific commit convention. Use short, imperative commit subjects, such as `Add input validation`. Pull requests should summarize the change and its motivation, identify related issues when applicable, and include test results. Add screenshots for changes that affect a visual interface.

## Security & Configuration

Keep credentials and machine-specific settings out of version control. Provide a sanitized example configuration if setup requires environment variables, and document required values without including secrets.
