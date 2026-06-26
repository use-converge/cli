# Converge CLI

Binary-only public releases for the Converge CLI.

Converge is currently in private beta. The CLI can be installed publicly, but useful API access requires a Converge account and API key.

## Install

```bash
brew tap use-converge/cli
brew trust --formula use-converge/cli/converge
brew install converge
```

Manual release archives are available from the [releases page](https://github.com/use-converge/cli/releases).

## Configure

```bash
export CONVERGE_BASE_URL="https://your-converge-host.example"
export CONVERGE_API_KEY="cvg_..."
```

You can also use `~/.config/converge/config.toml` for reusable profiles.

## Source

This repository intentionally does not contain source code. It exists only to distribute public CLI binaries and checksums from the private Converge build.
