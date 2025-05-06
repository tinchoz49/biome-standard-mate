# Biome Standard Mate

A modern JavaScript/TypeScript linting and formatting configuration based on NeoStandard, powered by Biome.

## Overview

This project provides a robust configuration for Biome, a fast formatter, linter, and more for JavaScript, TypeScript, JSON, and more. The configuration is inspired by NeoStandard and includes a comprehensive set of rules for maintaining high-quality code.

## Features

- 🚀 Fast and efficient linting and formatting
- 📝 Comprehensive rule set for JavaScript and TypeScript
- 🎨 Consistent code style across your project
- 🔒 Security-focused rules
- 🧹 Automatic import organization
- ⚡️ Git integration for better performance

## Installation

```bash
npm install --save-dev @biomejs/biome biome-standard-mate
```

## Configuration

```jsonc
{
  "$schema": "https://biomejs.dev/schemas/2.0.0-beta.2/schema.json",
  "extends": ["biome-standard-mate/biome"]
}
```

## Usage

### Format and Lint

```bash
npx @biomejs/biome format .
npx @biomejs/biome lint .
```

### Check

```bash
npx @biomejs/biome check .
```

## Key Features

The project uses a `biome.jsonc` configuration file that includes:

- Formatter settings (spaces, line width, etc.)
- Linter rules for:
  - Complexity
  - Correctness
  - Security
  - Style
  - Suspicious code patterns
- TypeScript-specific overrides
- Import organization rules

### Formatter Settings
- 2-space indentation
- 120 character line width
- LF line endings
- Single quotes for JavaScript
- Double quotes for JSX
- Trailing commas
- Semicolons as needed

### Linting Rules
- Strict type checking
- Security best practices
- Code complexity management
- Style consistency
- Suspicious code detection

### TypeScript Support
- Special handling for TypeScript files
- React-specific rules for TSX files
- Proper type checking

## VS Code Integration

The project includes VS Code settings for optimal development experience. Make sure to install the Biome extension for VS Code.

## Contributing

Feel free to submit issues and enhancement requests!

## License

ISC © Martin Acosta