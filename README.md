# ask.sh

Minimalist CLI interface for OpenAI's LLMs.

## Dependencies
- sh
- curl
- jq

## Usage

```bash
ask "Your question here"
```

The `!` prefix switches to higher reasoning mode:

```bash
ask ! "Explain quantum computing in simple terms."
```

Upon first run you'll be prompted to enter your OpenAI API key, which will be stored in `~/.ask.sh/api_key.txt`.

## Installation

```bash
curl -fsSL https://raw.githubusercontent.com/q009/ask.sh/main/ask | bash -s -- --install _
```

## Update

```bash
ask --install
```

## Uninstall

```bash
ask --uninstall
```
