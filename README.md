# LOLA Market

Connect Claude to [LOLA Market](https://lola.market) through the LOLA remote MCP
server. Once installed and signed in, Claude can work with your LOLA account —
browsing and managing listings, inventory and rentals, and running AI-assisted
pricing suggestions — directly from your conversation.

## Installation

Install the plugin from the Claude plugin directory, or add it directly:

```
/plugin install lola-market --marketplace lola-market/lola-market-plugin
```

On first use, Claude opens a browser window so you can sign in to
your LOLA Market account; authentication is handled over OAuth and no token or
secret needs to be pasted or stored locally.

## What it provides

This plugin bundles a single remote MCP server (`lola`). It ships no commands,
hooks, or local code of its own — all tools are served by the hosted LOLA MCP
endpoint, so the set of available tools reflects whatever the server currently
exposes.

## Authentication & data

Authentication uses a browser-based OAuth flow against LOLA Market. Requests you
make through the plugin's tools are sent to the LOLA MCP endpoint operated by
LOLA Market and are subject to LOLA Market's privacy policy and terms. The
plugin itself stores no credentials.

## Support

Questions and issues: https://lola.market
