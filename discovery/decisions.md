# Product decisions

Each decision records the context, the options considered, what was chosen and why. Decisions can be revisited when new evidence comes in.

## D1 · Compare two routes instead of rating one

- **Context:** people want to decide for themselves how much detour is worth it.
- **Options:** (a) show one “safe” route; (b) give each route a star rating; (c) show the fastest and a safer route side by side.
- **Decision:** (c), with the extra time shown.
- **Why:** it keeps the user in control and makes the trade-off visible.

## D2 · Explain *why*, in plain language

- **Context:** a route without an explanation isn’t trusted (hypothesis 2).
- **Decision:** each route shows its top 2–3 reasons, e.g. “well-lit streets most of the way”, “places open along the route”.
- **Why:** builds trust and lets people judge for themselves.

## D3 · “Safer”, never “safe”

- **Decision:** the app always compares routes and never claims a street is safe. When routes are too similar to call, it says so.
- **Why:** honesty about what the app can and can’t know; protects users and the product.

## D4 · Share a walk without waiting

- **Context:** if the person you want to share with has to accept something first, you’ve already left.
- **Decision:** trusted contacts are set up in advance; anyone else gets a one-time link, with no app or account needed.
- **Why:** sharing must never delay the walk.

## D5 · Cap the detour

- **Context:** long detours push people to take a ride instead (hypothesis 3).
- **Decision:** the safer route is only suggested within a maximum extra time; otherwise the app says no clearly better option exists.

## What I chose *not* to build (for now)

| Left out | Why |
|---|---|
| SOS / emergency features | Other apps cover this; the value is in planning before leaving (hypothesis 5). The app states clearly that it isn’t an emergency service. |
| Crime maps or “dangerous area” labels | They stigmatise neighbourhoods and the people who live there |
| Communities, chat, free-text reports | Hard to moderate; risk of misuse and of describing people instead of places |
| Other cities | Prove the idea works in one city first |
| Running routes | A different need (hypothesis 7) |
