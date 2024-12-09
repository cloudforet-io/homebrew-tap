# Cloudforet Homebrew Tap

This repository contains Cloudforet's Homebrew (macOS package manager) formulae.

## Available Formulae

- `cfctl`: Command-line interface for SpaceONE that provides easy access to Cloudforet services

## Installation

First, add this tap to your Homebrew:

```bash
brew tap cloudforet-io/tap
```

Then, install the packages you want:

```bash
brew install cfctl
```

## Updating

To update the formulae and then upgrade the installed packages:

```bash
brew update
brew upgrade cfctl
```

## Development

These formulae are automatically updated by GoReleaser when a new version of cfctl is released.

## License

Apache License 2.0

## Links

- [Cloudforet Documentation](https://docs.spaceone.megazone.io/)
- [cfctl Repository](https://github.com/cloudforet-io/cfctl)
