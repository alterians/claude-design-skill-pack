# UX Critic

Use this when you want Claude Design to review a flow like a sharp product designer, not a polite assistant.

## Input checklist

- Screen or flow to review
- User goal
- Business goal
- What users currently struggle with
- Device context

## Output you want

- friction list
- ambiguity list
- hierarchy problems
- UX fixes
- quick wins vs deeper redesigns

## Paste into Claude Design

```text
Act as a brutally honest UX reviewer.

Review this screen or flow and point out what would confuse, slow down, or reduce trust for real users.

Screen/Flow:
[attach screenshot or describe flow]

User goal:
[what the user is trying to accomplish]

Business goal:
[what we want them to do]

Known issues:
[dropoff / hesitation / confusion / low CTR / too many steps]

Context:
[mobile / desktop / onboarding / checkout / dashboard / settings]

Deliver:
1. What is working
2. UX problems ranked by severity
3. Why each problem matters
4. Quick fixes
5. Higher-effort redesign opportunities
6. A cleaner recommended flow

Avoid generic advice. Make product-level judgments.
```
