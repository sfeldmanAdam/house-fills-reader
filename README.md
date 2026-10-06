# House Fills Reader

A private, read-only tool. It connects one Alpaca brokerage account, its owner's own, and reads that account's trade fills each evening to build the owner's daily profit-and-loss report. It is not offered to anyone else.

## What it reads

It asks Alpaca for no OAuth scopes, so it holds read-only access. It reads only:

- `GET /v2/account`, to confirm the connected account is the owner's.
- `GET /v2/account/activities/FILL`, the account's fills for a given day.

It never places, changes or cancels an order, never moves money, and never changes an account setting.

## Terms of Use

- The tool is for its owner's personal use only. It has no other users and accepts no sign-ups.
- It is provided as is, with no warranty of any kind.
- The account owner can end its access at any time by revoking the connection in the Alpaca dashboard.

## Privacy Policy

- The tool reads only its owner's own account data: the account check and that account's fills.
- It stores those fills only on the owner's own computer.
- It shares no data with anyone, sells nothing, and holds no data about any other person.
- Revoking the connection in the Alpaca dashboard stops all access at once.

Last updated October 6, 2026.
