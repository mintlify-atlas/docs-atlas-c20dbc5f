# Ward Documentation

This repository contains the documentation for [Ward](https://github.com/Eljakani/ward), a security scanner built for Laravel.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation locally:

```bash
npm i -g mint
```

Run the following command at the root of your documentation:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing Changes

Changes pushed to the `main` branch are automatically deployed to production.

## Documentation Structure

- **Get Started** - Introduction, installation, and quickstart guide
- **Core Concepts** - Architecture, scan pipeline, and security scanners overview
- **Command Reference** - Complete CLI command documentation
- **Configuration** - Config file, custom rules, output formats, and rule overrides
- **Guides** - CI integration, baseline management, custom rule writing, and understanding findings
- **Scanners** - Detailed documentation for each scanner type
- **API Reference** - CLI options, exit codes, rule schema, and report formats
