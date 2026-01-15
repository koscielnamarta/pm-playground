# MVP Scope

_Last updated: 2026-01-15_

# Happy-Path User Flow — AI Tarot App

## Preconditions
- User has a physical tarot deck
- User has a question or topic in mind
- User wants reflection, not prediction

## Step-by-step flow
1. User selects a tarot spread (e.g. 3-card, Celtic Cross)
2. User lays out physical cards according to the spread
3. User takes a photo of the spread
4. User optionally adds a short textual question or context
5. System identifies cards and their positions
6. AI generates a holistic interpretation of the full spread
7. User reflects on the interpretation

## Output principles
- Interpretation focuses on patterns, themes, and tensions
- Language is reflective, not deterministic
- Multiple perspectives are allowed, not a single “truth”

## Edge case to be covered in the next steps
- If the system has issues with card detection (non-standard deck, low quality photo, etc.), the user manually overrides / selects the correct card

## Explicit product boundaries (important)

This product intentionally does NOT:
- predict concrete future events
- give medical, legal, or financial advice
- replace the user’s own intuition or judgment
- claim absolute or objective truth
- provide yes/no answers to life decisions
