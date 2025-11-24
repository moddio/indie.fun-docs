# Token Sale – Oversubscription Handling

## Context

When a token sale is oversubscribed - meaning more SOL is raised than the intended goal - Indie.fun uses an overallocation mechanism to fairly distribute tokens and refund excess contributions.

Note that this means the fundraise ends when the time limit expires, *not* when the fundraising goal is reached.

This ensures:
- Every user receives tokens in proportion to what they contributed relative to the amount raised,
- Each user can back any amount, with any oversubscription automatically refunded,
- The dev receives only the fundraise goal amount.

---

## Key Mechanics

- Token allocation is calculated based on the target raise (e.g. 500 SOL).
- Users receive tokens in proportion to their accepted contribution.
- Any SOL above their accepted allocation (any oversubscription) is automatically refunded.

---

## Example 1: Simple Overallocation

Let’s say:
- Fundraising target: 500 SOL
- Total raised: 1000 SOL (2× oversubscribed)
- Public token pool: 100,000,000 tokens

| User | Amount Sent | Accepted SOL | Refund | Token Allocation |
|------|-------------|--------------|--------|------------------|
| A    | 100 SOL     | 50 SOL       | 50 SOL | 10,000,000       |
| B    | 900 SOL     | 450 SOL      | 450 SOL| 90,000,000       |
| **Total** | **1000 SOL** | **500 SOL** | **500 SOL** | **100,000,000** |

---

## Bonus Allocation

Devs can enable token bonuses for selected backers during their fundraise. These bonuses increase the number of tokens a backer receives, relative to those without a bonus.

### Types of Bonuses

- **Whitelist Bonus:** For example, a dev might allow:
  - VIP Whitelist: +10% tokens
  - General Whitelist: +5% tokens
- **Referral Bonus:** Devs can generate unique referral links. If a user backs via a referral link, they can receive a bonus.

> Bonuses stack, but the total bonus is capped at 10%.

### Timing Matters

Bonuses only apply if the backer contributes during the eligible bonus period. For instance, if a VIP Whitelist lasts 30 minutes, a backer must contribute within that window to receive the bonus. Backing after the window ends means no bonus applies.

---

## Refund Timing

All refunds are processed and sent automatically after the fundraise time ends.

