---
id: quadratic-voting
name: Quadratic voting
type: tested-local
role: add-on
scores: {F: 4, P: 4, S: 3, C: 3, R: 2, E: 2}
related: [liquid-democracy, participatory-budgeting]
updated: 2026-11-07
---

# Quadratic voting

**In one line:** each voter gets a budget of credits; casting n votes on one issue costs n² credits, so people can express how strongly they care.

## Mechanism
- Everyone receives equal credits.
- 1 vote = 1 credit, 2 votes = 4, 3 votes = 9.
- Voters spread credits across issues according to intensity of preference.
- Related: quadratic funding, which matches donations in proportion to the number of contributors rather than amount.

## Origins
- Steven Lalley and E. Glen Weyl; popularized in *Radical Markets* (2018) [posner2018].

## Real-world use
- Colorado House Democrats used it in 2019 to prioritize bills.
- Taiwan's Presidential Hackathon used it to judge projects.
- Gitcoin uses quadratic funding for open-source grants.

## Strengths
- Protects passionate minorities from indifferent majorities.
- Reveals priorities, not just yes/no positions.

## Weaknesses
- Vulnerable to collusion and fake identities (splitting into many accounts beats the quadratic cost).
- Harder to understand than one person, one vote.
- Untested for binding, high-stakes public decisions.

## Open questions
- Can identity verification make it secure without harming privacy?
