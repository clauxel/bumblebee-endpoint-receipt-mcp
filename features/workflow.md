# Workflow

Bumblebee Endpoint Receipt is a hosted remote MCP for developer endpoint scanner MCP.

## Repeatable Flow

1. Open Bumblebee Endpoint Receipt and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://bumblebeereceipt.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call scan_endpoint_exposure with public-safe sample data.
5. Save the returned receipt or export for human review.

## Output Mindset

The useful artifact is not a marketing claim. It is evidence that a reviewer can inspect, export, and compare later.
