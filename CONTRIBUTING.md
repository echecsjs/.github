# Contributing

## Prerequisites

- [Node.js](https://nodejs.org/) >= 20
- [pnpm](https://pnpm.io/) (used as the package manager)

## Setup

Fork the repository, clone it, and install dependencies:

```bash
pnpm install
```

## Development Workflow

### Running tests

```bash
pnpm test
```

Watch mode during development:

```bash
pnpm test:watch
```

### Linting and formatting

```bash
pnpm lint
pnpm format
```

### Building

```bash
pnpm build
```

## Submitting Changes

1. Fork the repository and create a branch from `main`.
2. Make your changes, including tests for any new behaviour.
3. Ensure all checks pass: `pnpm lint && pnpm test && pnpm build`.
4. Open a pull request describing what you changed and why.

## Reporting Bugs

Open an issue and include:

- A minimal reproducible example
- Expected vs. actual behaviour
- Your Node.js and package version

## Commit Style

Keep commits focused and use clear messages. No specific convention is enforced,
but describe the _why_, not just the _what_.

## License

By contributing you agree that your contributions will be licensed under the
[MIT License](LICENSE).
