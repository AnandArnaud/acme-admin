# acme-admin

Acme Admin is a tiny internal admin panel — sign in, manage products, sign out.

**Stack:** Plain HTML / CSS / JS (no build step)

It is realistic but intentionally small, and ships with **no product analytics, experimentation, or session-replay wired in** — the user-action handlers just log to the console today.

## User actions worth tracking

sign in · create product · delete product · sign out

## Running it

```bash
# static site — no build
python3 -m http.server 8000   # then open http://localhost:8000
```
