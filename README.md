# Homebrew tap for Sleet

[Sleet](https://github.com/nekocentral/Sleet) reads and updates ServiceNow tickets from your terminal.

## Install

```bash
brew install nekocentral/sleet/sleet
```

This works on macOS and on Linux with Homebrew. It installs Sleet with `requests` and PyYAML in an environment of its own.

Then set up your configuration and session cookie as described in the [Sleet README](https://github.com/nekocentral/Sleet#install).

## Update

```bash
brew update
```

```bash
brew upgrade sleet
```

## How this tap is kept up to date

A workflow checks once a day for a new Sleet release tag and updates the formula's version and checksum. To update right after a release, run the "Update formula" workflow by hand from the Actions tab.

The Python packages Sleet depends on are pinned in the formula and are not updated automatically.
