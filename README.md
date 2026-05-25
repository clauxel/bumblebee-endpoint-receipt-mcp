# Bumblebee Endpoint Receipt

Bumblebee Endpoint Receipt is a hosted remote MCP for developer endpoint scanner MCP.

This repository is a public documentation project for Bumblebee Endpoint Receipt. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://bumblebeereceipt.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=bumblebeereceipt_public_docs&utm_content=readme_home
- Pricing: https://bumblebeereceipt.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=bumblebeereceipt_public_docs&utm_content=readme_pricing
- Checkout: https://bumblebeereceipt.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=bumblebeereceipt_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://bumblebeereceipt.clauxel.com/mcp
- Server card: https://bumblebeereceipt.clauxel.com/server-card.json
- Registry name: `com.clauxel.bumblebeereceipt/bumblebeereceipt-mcp`
- Tools: `scan_endpoint_exposure`, `explain_package_hit`, `issue_release_receipt`, `read_scan_history`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: scan_endpoint_exposure
- MCP tool: explain_package_hit
- MCP tool: issue_release_receipt
- MCP tool: read_scan_history

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
