[update-readmes]   Mode: rewrite — migrating to template structure...
# clasp

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/clasp)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install


First download `clasp`:

```sh
npm install -g @google/clasp
```

Then enable the Google Apps Script API: https://script.google.com/home/usersettings

![Enable Apps Script API](https://user-images.githubusercontent.com/744973/54870967-a9135780-4d6a-11e9-991c-9f57a508bdf0.gif)

### Installing as a Gemini CLI Extension

You can install clasp as an Gemini CLI extensions using the following command:

```sh
gemini extensions install https://github.com/google/clasp
```

This makes clasp available as an MCP server in Gemini CLI. 

Make sure to enable the Google Apps Script API (as explained above) and perform a `clasp login` (with your specific login parameters) before you use the extension.

### Installing as a Claude Code CLI Extension

You can use clasp with Claude Code CLI in one of two ways:

#### 1. Install as a Plugin (Recommended)

Run the following command in Claude Code to install clasp as a plugin directly from the repository:

```sh
/plugin install @google/clasp
```

#### 2. Manual Installation

You can manually add clasp as an MCP server using the provided configuration file or by running:

```sh
claude mcp add clasp -- npx -y @google/clasp mcp
```

Or by referencing the configuration file included in the repository:

```sh
claude mcp add-json clasp "$(cat claude-mcp.json)"
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/clasp`](https://github.com/Interested-Deving-1896/clasp) and mirrored through:

```
Interested-Deving-1896/clasp  ──►  OpenOS-Project-OSP/clasp  ──►  OpenOS-Project-Ecosystem-OOC/clasp
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[Apache-2.0](https://github.com/Interested-Deving-1896/clasp/blob/master/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
