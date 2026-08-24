# Homebrew Tap for VoiceFi™ (`vifi`)

Official Homebrew tap for [VoiceFi™](https://voicefi.org) — Universal Voice Layer for AI coding agents (Antigravity & Claude Code), MCP, and macOS.

## Quick Install

```bash
# Add tap and install vifi in one line:
brew install atxatlarge-code/tap/vifi

# Or tap first:
brew tap atxatlarge-code/tap
brew install vifi
```

## Getting Started

Once installed, connect AI agent hooks and autostart companion:

```bash
# Register agent turn lifecycle hooks (Antigravity, Claude Code)
vifi setup

# Enable persistent Dynamic Island HUD & Menu Bar companion daemon
vifi autostart

# Test speech audio
vifi voice test

# Launch interactive web control panel
vifi panel
```

## Available Formulae

| Formula | Description |
| :--- | :--- |
| [`vifi`](Formula/vifi.rb) | VoiceFi CLI, AI Agent voice bridge, and macOS companion |
| [`voicefi`](Formula/voicefi.rb) | Alias for `vifi` |
