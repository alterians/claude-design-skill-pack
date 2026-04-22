# Design System Refactorer

Use this when a design looks inconsistent and you want Claude Design to impose order.

## Input checklist

- Screenshot or design export
- Product type
- Current issues
- Desired style level: startup clean, enterprise, editorial, bold, etc.

## Output you want

- color tokens
- typography scale
- spacing system
- component list
- states and usage rules
- cleanup recommendations

## Paste into Claude Design

```text
Act as a design systems lead.

I need you to extract and clean up the system behind this interface.

Reference:
[attach screenshot or describe the UI]

Current issues:
[inconsistent spacing / too many button styles / weak hierarchy / random colors / messy cards]

Desired feel:
[clean SaaS / premium / minimalist / high-trust / editorial]

Deliver:
1. Visual problems you see
2. Proposed color tokens
3. Proposed typography scale
4. Spacing and layout system
5. Core components that should exist
6. Variant and state recommendations
7. Refactor priorities from highest impact to lowest

Be specific enough that another designer or builder could execute it.
```
