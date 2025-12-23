# nicksp/workflows

A collection of reusable GitHub Actions workflows and actions for TypeScript projects.

## Features

- Standardized CI/CD workflows for testing, building, and releasing
- Easy integration into any TypeScript repository
- Includes custom actions for setup and automation

## Included Workflows

- Test: Runs tests and lints code
- Release: Publishes releases to npm
- Preview Release: Triggers an instant preview release without publishing anything to NPM

## Included Actions

- `setup-repo`: Sets up repository, installs Node.js and dependencies

## Usage

To use a workflow, reference it in your project’s `.github/workflows/*.yml`:

```yaml
# Example: Unit Test
name: Test
uses: nicksp/workflows/.github/workflows/test.yml@main
```

## License

[MIT](LICENSE) License &copy; 2025 [Nick Plekhanov](https://plekhanov.me)
