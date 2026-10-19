# England Works Watch

Public connector metadata for the hosted **England Works Watch** MCP service operated by RegEvidenceHub.

## Remote MCP

`https://works.regevidencehub.com/mcp`

This repository contains public installation and service-discovery metadata for the hosted MCP service.

## What it does

Evidence-linked UK Skilled Worker sponsor-change preflight and compliance monitoring for employer, HR, and agent workflows.

## Installation

Use the remote MCP endpoint above, or import the included `.mcp.json` in clients that support MCP configuration files.

## Payment

Agent-native paid MCP actions use x402 where payment is required. Human-facing premium checkout remains available separately through RegEvidenceHub.

## Verified marketplace listing

PayAPI Market has independently settled and verified a paid execution of the commercial Sponsor / England Works Watch route:

https://payapi.market/api/regevidencehub-sponsor-england-works-watch

Agents can also discover paid APIs through the PayAPI MCP directory at https://payapi.market/mcp.

## Publisher

RegEvidenceHub — https://www.regevidencehub.com/


## Gemini CLI

Install this connector as a Gemini CLI extension:

```sh
gemini extensions install https://github.com/ChanghuLiu/england-works-watch-connector
```

The Gemini CLI extension connects to the hosted Streamable HTTP MCP endpoint above. Gemini CLI does not automatically sign x402 payments; paid tools may return a payment-required response and need a separate x402-capable payment workflow. Do not put wallet private keys in this extension.
