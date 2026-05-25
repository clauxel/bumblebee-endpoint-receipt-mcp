# Evaluation Guide

Use this page to evaluate whether Bumblebee Endpoint Receipt fits a real workflow.

## What To Test

- developer endpoint scanner MCP
- Bumblebee Endpoint Receipt
- Bumblebee Endpoint Receipt documentation
- Bumblebee Endpoint Receipt remote MCP
- bumblebeereceipt server card

## Expected Evidence

- Open Bumblebee Endpoint Receipt and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://bumblebeereceipt.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call scan_endpoint_exposure with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://bumblebeereceipt.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=bumblebeereceipt_public_docs&utm_content=evaluation_checkout
